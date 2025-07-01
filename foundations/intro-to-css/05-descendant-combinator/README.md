后代组合器

当你开始动手实践组合器，并观察哪些东西被它们影响、哪些没有时，理解它们的工作原理会变得容易得多。

本次练习的目标是，为作为另一个元素后代的元素应用样式，同时保持那些不是该元素后代的元素没有样式。

在这个练习中，你可以使用类型选择器或类选择器；用你觉得更想练习的那一种即可。HTML 文件已经设置好了（所以无需编辑其中的任何内容），任何选择器的组合都能工作，所以如果你想挑战一下，你甚至可以尝试为后代组合器组合一个类型和一个类选择器。

你需要添加的属性是：

只有作为 div 元素后代的 p 元素，才应该有黄色背景、红色文本、20px 的字号，并且居中对齐。

期望结果

![alt text](./desired-outcome.png)

自我检查

包含文本 “This should be styled” 的元素是否应用了正确的样式？

包含文本 “This should be unstyled” 的元素是否没有任何样式被应用？


# Descendant Combinator
Understanding how combinators work can become a lot easier when you start playing around with them and see what exactly is affected by them versus what isn't.

The goal of this exercise is to apply styles to elements that are descendants of another element, while leaving elements that *aren't* descendants of that element unstyled.

You can use either type or class selectors for this exercise; use whichever you may feel you want to practice with more. The HTML file is set up (so no need to edit anything in it) such that any combination of selectors will work, so if you're feeling adventurous you can even try combining a type *and* class selector for the descendant combinator.

The properties you need to add are:

* Only the `p` elements that are descendants of the `div` element should have a yellow background, red text, a font size of 20px, and center aligned.

## Desired Outcome
![desired outcome](./desired-outcome.png)


### Self Check
- Do the elements that contain the text "This should be styled" have the correct styles applied?
- Do the elements that contain the text "This should be unstyled" have no styles applied?
