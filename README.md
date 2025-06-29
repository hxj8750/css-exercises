CSS 练习

这些练习包含一系列与 CSS 相关的任务，旨在作为 The Odin Project (TOP) 上 HTML 和 CSS 内容的补充。这些练习只应在课程中被指示时才去完成。

在做这些练习时，请使用所有你需要的文档和资源来完成它们。我们不期望你在现阶段就记住任何这些东西。查阅文档、使用谷歌、做任何你需要做的事情（除了查看答案）来完成它们。

重要提示

我们鼓励你通过提交你的更改并将它们推送到你自己的 fork 来练习你的 git 技能。然而，请不要开启一个 Pull Request (PR) 来请求将你的解决方案合并到这个仓库，或者只是为了展示你的解决方案。如果我们合并了你的更改，这些练习就不再能按预期为新学员服务了，而开启一个 PR 只会给我们带来额外的工作，因为我们必须在不合并的情况下关闭它。

贡献

如果你有改进某个练习的建议、新练习的想法，或者注意到某个练习有问题，请在彻底阅读我们的贡献指南后，随时开启一个 issue。

如何使用这些练习

Fork 并 clone 这个仓库。

要学习如何 fork 一个仓库，请参阅 GitHub 关于如何 fork 一个 repo 的文档。

你机器上的仓库副本被称为 clone (克隆)。如果你需要帮助将仓库克隆到你的本地环境，你可以从 GitHub 关于克隆一个仓库的文档中学习。

进入一个练习目录，并在网页浏览器中打开 HTML 文件。你可以直接打开文件，或者使用像 VSCode 的 Live Server 扩展这样的工具。

对于每个练习，在开始任何工作前，彻底阅读 README。

每个 README 都有一个 “Self Check” (自我检查) 列表。用它来确保你在实现中没有错过任何重要的细节。

在 index.html 和/或 style.css 文件中进行你的编辑，以使你在浏览器中的输出看起来像**“期望结果” (Desired Outcome)** 的图片一样。

根据练习的指示，你可能只需要在其中一个文件中进行编辑。

一旦你成功完成一个练习，查看 TOP 的解决方案来与你的方案进行比较。

在你完成一个练习之前，你不应该查看它的解决方案！

如果你的解决方案与 TOP 的解决方案大相径庭（但仍然满足练习的要求），那完全没问题。如果其中有你不理解的部分，请随时在我们的 Discord 中提问。

重要提示

不要将你的解决方案提交到这个 repo，任何这样做的 PR 都将在不合并的情况下被关闭。
一些提示

官方解决方案将所有更改都放在 CSS 文件的末尾，这可能会重复一些选择器（例如，给定的 CSS 中可能有一个 body {}，解决方案中又有一个 body {}）。当你在做练习时，最佳实践是将你的 CSS 添加到现有的选择器中，而不是在文件末尾重复它们。我们在官方解决方案中牺牲了这种最佳实践，是为了让你格外清楚地看到我们为了解决练习而改变了哪些东西。

除非在自我检查部分列出，否则不必担心为像 margin、padding 和 font-size 这样的东西获取精确的像素值。这些练习旨在测试你的 CSS 知识，而不是测试你猜测截图使用的是 font: sans-serif bold 16px 或者 margin 恰好是 42px 的能力。

你可能需要向你的 HTML 中添加一些元素来把东西放到正确的位置。（对于最初的几个练习，当需要这样做时，我们会明确指出。）

你可能需要向你的 CSS 文件中添加更多的选择器。最初的几个练习几乎所有东西都已为你准备好，但随着你不断进步，你会发现你需要添加越来越多的选择器来得到正确的结果。

# CSS Exercises

These exercises consist of a series of CSS-related tasks intended to complement the HTML and CSS content on The Odin Project (TOP). They should only be completed when instructed during the course of the curriculum.

When doing these exercises, please use all documentation and resources you need to accomplish them. You are _not_ intended to have any of this stuff memorized at this point. Check the docs, use Google, and do what you need to do (besides checking the solutions) to get them done.

> [!IMPORTANT]
> We encourage you to practice your git skills by committing your changes and pushing them to your own fork.  However, please **DO NOT** open a Pull Request to have your solutions merged into this repo or to show your solution.  If we were to merge your changes the exercises would no longer be available as intended for new learners, and opening a PR only causes additional work for us, as we have to close it without merging.

## Contributing

If you have suggestions to improve an exercise, ideas for a new exercise, or notice an issue with an exercise, please feel free to open an issue after thoroughly reading our [contributing guide](https://github.com/TheOdinProject/.github/blob/main/CONTRIBUTING.md).

## How To Use These Exercises

1. Fork and clone this repository. To learn how to fork a repository, see the GitHub documentation on how to [fork a repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
    - Copies of repositories on your machine are called clones. If you need help cloning to your local environment, you can learn how from the GitHub documentation on [cloning a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
1. Go to an exercise directory and open the HTML file in a web browser. You can open the file directly or use something like VSCode's Live Server extension.
1. For each exercise, read the README thoroughly before starting any work.
    - Each README has a "Self Check" list. Use this to ensure you haven't missed any important details in your implementation.
1. Make your edits in the `index.html` and/or the `style.css` files in order to make the output in your browser look like the Desired Outcome image(s).
    - Depending on the instructions of the exercise, you may only need to make edits in one of these files.
1. Once you successfully finish an exercise, check TOP's solution to compare it with yours.
    - You should not be checking the solution for an exercise until you finish it!
    - If your solution differs wildly from TOP's solution (and still passes the exercise's requirements), that's completely fine. Do feel free to ask about it in our Discord if there are parts you do not understand.

> [!IMPORTANT]
> Do not submit your solutions to this repo, as any PRs that do so will be closed without merging.

## Some Hints
- The official solutions put all changes at the _end_ of the CSS file, which may duplicate some selectors (e.g. there might be a `body {}` in the given CSS and another `body {}` in the solution). When you are working on an exercise, it is best practice to add your CSS to existing selectors instead of duplicating them at the end of the file. We're sacrificing this best practice in our official solutions to make it extra clear to you what things we changed to solve the exercise.
- Unless listed in the self-check section, do not worry about getting the exact pixel value for things like margin, padding and font size. These exercises are intended to test your knowledge of CSS, not your ability to guess that a screenshot is using `font: sans-serif bold 16px` or that the margin is _exactly_ `42px`.
- You may need to add some elements to your HTML to get things into the right spot. (For the first few exercises, we make it explicit when this needs to happen.)
- You may need to add more selectors to your CSS file. The first few exercises have almost everything already done for you, but as you progress, you'll find that you need to add more and more selectors to get the correct result.
