链式选择器

本次练习中图片的版权归 Katho Mutodo 和 Andrea Piacquadio 所有。

在这个练习中，我们为你提供了一个部分完成的 HTML 文件，你将对其进行配置。本次练习的目的是专注于理解如何链接 (chain) 不同的选择器，而不仅仅是添加属性。此外，你将有机会复习你的 HTML 图片知识。

我们有两张图片需要你来设置样式，每张图片都有两个类名，其中一个类名是共享的。这里的目标是为这两个元素链接选择器，以便尽管它们使用了一个共享的类选择器，但每个元素都能被应用上独特的样式。例如，你希望一个同时拥有 X 和 Y 的元素有一套样式，而一个同时拥有 X 和 Z 的元素则有完全不同的另一套样式。我们也包含了原始图片，以便你可以看到你将要添加的样式与之相比是什么样子，所以不要为原始图片添加任何样式。

你需要为每个元素添加的属性是：

使同时拥有 avatar 和 proportioned 这两个类的元素宽度为 300 像素，然后给它一个高度，使其保持其原始的正方形比例（不要为高度硬编码一个像素值！）。

使同时拥有 avatar 和 distorted 这两个类的元素宽度为 200 像素，然后使其高度是其宽度的两倍（这里你应该硬编码一个像素值）。

期望结果

![alt text](./desired-outcome.png)

自我检查

你是否为每条规则正确地链接了类选择器？

proportioned 图片是否保持了其原始的正方形比例？

distorted 图片最终是否看起来被压扁了，嗯，就是扭曲了？


# Chaining Selectors

Credits for the images in this exercise go to [Katho Mutodo](https://linktr.ee/photobykatho_) and [Andrea Piacquadio](https://www.pexels.com/@olly?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels).


With this exercise, we've provided you with a partially completed HTML file which you'll configure. The purpose of this exercise is to focus on understanding how to chain different selectors, rather than solely adding attributes. Additionally, you'll have the chance to review your HTML images.

We have two images for you to style, each with two class names, where one of the class names is shared. The goal here is to chain the selectors for both elements, so that each have a unique style applied, despite using a shared class selector. For example, you want an element that has both X and Y to have one set of styles, while an element with X and Z has a completely different set of styles. We included the original images as well, so that you can see how the styles you will be adding look in comparison, so do not add any styles to them.

The properties you need to add to each element are:

* Make the element with both the `avatar` and `proportioned` classes 300 pixels wide, then give it a height so that it retains its original square proportions (don't hardcode in a pixel value for the height!).
* Make the element with both the `avatar` and `distorted` classes 200 pixels wide, then make its height twice as big as its width (here you should hardcode in a pixel value).

## Desired Outcome
![desired outcome](./desired-outcome.png)

### Self Check
- Did you properly chain class selectors for each rule?
- Does the `proportioned` image retain its original square proportions?
- Does the `distorted` image end up looking squished and, well, distorted?
