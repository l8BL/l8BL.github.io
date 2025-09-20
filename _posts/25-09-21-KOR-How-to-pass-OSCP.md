---
layout: post
title: "[KOR] OSCP+ Review"
subtitle: How I passed OSCP+
categories: Ceriticates
tags:
  - pentest
  - oscp
---

25년 8월 15일 OSCP+ 시험을 응시했고, 8월 21일에 합격 통보를 받았다.
![[Pasted image 20250921011837.png]]

OSCP+는 실전 위주의 시험이라 재밌게 준비할 수 있는 시험이었던 것 같다. 특히 어플리케이션 단의 취약점에 한정되어 있었던 내 시야를 인프라 측면까지 조금 더 넓게 볼 수 있게 만들어 줬다.

## 준비 

### OSCP 교안

해외 커뮤니티를 돌아다니다 보면, OSCP 교안이 도움이 된다 안된다에 대해서는 논쟁이 많다. 



#### 문제풀이
문제 풀이는 HacktheBox 머신을 풀었는데, 이 시점부터는 TJNull's machine List 가 아닌 Lainkusanagi OSCP Like List 를 참고하기 시작했다.
https://docs.google.com/spreadsheets/d/18weuz_Eeynr6sXFQ87Cd5F0slOj9Z6rt/edit?gid=487240997#gid=487240997

Machine List를 바꾼 이유는 Lainkusanagi는 Assumed Breach Scenario 문제를 별도로 정리해뒀으며, 조금 더 문제들이 OSCP 실전과 가깝다고 느꼈기 때문이다. 

HacktheBox 문제 풀이를 하고 이제는 단순히 답지만 참고하는게 아니라 IppSec 의 풀이랑 비교하면서 매일매일 얻는 지식을 기록했다. 
https://www.youtube.com/@ippsec

대강 도식화하면 아래와 같다.
![[hackthebox_methodology (1).png]]

새로운 도구 활용법이나 커맨드 사용법은 기록해두는게 좋은 것 같다. 파일 편집하는 커맨드까지 전부 습득하면 다양한 환경에서 추후 도움이 많이 됐던 것 같다.






## 교훈

OSCP+ 를 결제하고 보다 보면 초반 부가 생각보다 뜬구름 잡는 얘기로 보인다. 왜냐하면 생각보다 해당 자격증이 다루고 있는 부분이 방대하기 때문이다. 정보보호개론에 나올 법한 CIA Triad 부터 제도 및 보고서 작성 방법까지 워낙 넓은 부분을 다루고 있기 때문에 자격증에 들어간 돈이 아깝다고 모든 부분을 외우려고 접근하면 정말정말 힘들게 볼 수 밖에 없다.





*Note: Feel free to play with this page. Unlike regular notes, this doesn't automatically save itself.*

## Basic formatting

Paragraphs can be written like so. A paragraph is the basic block of Markdown. A paragraph is what text will turn into when there is no reason it should become anything else.

Paragraphs must be separated by a blank line. Basic formatting of *italics* and **bold** is supported. This *can be **nested** like* so.

## Lists

### Ordered list

1. Item 1
2. A second item
3. Number 3
4. Ⅳ

*Note: the fourth item uses the Unicode character for [Roman numeral four][2].*

### Unordered list

* An item
* Another item
* Yet another item
* And there's more...

## Paragraph modifiers

### Code block

    Code blocks are very useful for developers and other people who look at code or other things that are written in plain text. As you can see, it uses a fixed-width font.

You can also make `inline code` to add code into other things.

### Quote

> Here is a quote. What this is should be self explanatory. Quotes are automatically indented when they are used.

## Headings

There are six levels of headings. They correspond with the six levels of HTML headings. You've probably noticed them already in the page. Each level down uses one more hash character.

### Headings *can* also contain **formatting**

### They can even contain `inline code`

Of course, demonstrating what headings look like messes up the structure of the page.

I don't recommend using more than three or four levels of headings here, because, when you're smallest heading isn't too small, and you're largest heading isn't too big, and you want each size up to look noticeably larger and more important, there there are only so many sizes that you can use.

## URLs

URLs can be made in a handful of ways:

* A named link to [MarkItDown][3]. The easiest way to do these is to select what you want to make a link and hit `Ctrl+L`.
* Another named link to [MarkItDown](https://www.markitdown.net/)
* Sometimes you just want a URL like <https://www.markitdown.net/>.

## Horizontal rule

A horizontal rule is a line that goes across the middle of the page.

---

It's sometimes handy for breaking things up.

## Images

Markdown can also contain images. I'll need to add something here sometime.

## Finally

There's actually a lot more to Markdown than this. See the official [introduction][4] and [syntax][5] for more information. However, be aware that this is not using the official implementation, and this might work subtly differently in some of the little things.


  [1]: https://daringfireball.net/projects/markdown/
  [2]: https://www.fileformat.info/info/unicode/char/2163/index.htm
  [3]: https://www.markitdown.net/
  [4]: https://daringfireball.net/projects/markdown/basics
  [5]: https://daringfireball.net/projects/markdown/syntax
