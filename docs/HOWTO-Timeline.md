[TOC]

# How To Use Notes

[Notes](/notes) is a web-based tool that helps you manage knowledge bases by organizing your bookmarks and notes as answers to questions you care about.  Like other bookmarking sites such as [Pinboard](https://pinboard.in/about/), Instapaper, and Pocket etc., Notes adds a [small button](#how-to-use-bookmarklet) to your browser that lets you remember things you read, giving you the chance to label them with tags and descriptive text. 

Other than common bookmarking site features, SaveNowClub Notes offers the following unique features:

* SaveNowClub Notes allow you to organize your bookmarks and notes as answers to  questions or posts under topics.  There are a lot more notes than number of questions/topics because questions/topics are relatively high-level because they represent major areas of your attention at certain time.  In addition to using hashtags, your saved bookmarks or notes can be found by finding the question it answers or the topic it relates to. Users manage topics for notes using [parent chooser](#how-to-use-parent-chooser) tool.
* SaveNowClub Notes allows you to see track records of a predictor by [using facts to validate predictions](#how-to-track-predictor-performance). 

# How to Use Bookmarklet

SaveNowClub uses bookmarklets for bookmarking web content. Bookmarklets are little javascript links that live in the bookmarks toolbar of your browser.

Here's the bookmarklet we offer: <a href="javascript:q=location.href;if(document.getSelection){d=document.getSelection();}else{d='';};p=document.title;void(open('https://savenowclub.com/notes/submit?url=%27+encodeURIComponent(q)+%27&description=%27+encodeURIComponent(d)+%27&title=%27+encodeURIComponent(p),%27Pinboard%27,%27toolbar=no,width=550,height=400%27));">popup</a> opens a little form window when you want to save a page. It's the fastest way to add content from a web URL.

How to Install and Use Bookmarklet: if you need help to install and/or use our bookmarklet, please refer [this guide](https://www.howtogeek.com/189358/beginner-geek-how-to-use-bookmarklets-on-any-device/).

## Issue with Bookmarklet on Android Chrome

This bookmarklet has been tested working on Chrome browser on PC, Mac and iPhone.  On Chrome browser on an Android phone, clicking this bookmarklet may not open up popup form, if that happens, use the method in [this tutorial](https://paul.kinlan.me/use-bookmarklets-on-chrome-on-android/) can solve that problem. 

# How to Use Parent Chooser

By default, saved notes are at top level. Picking a proper topic for it is a great way to organize the notes under proper theme for later reference.  You may use `Parent Chooser` tool located on each note page to quickly create or pick existing uncertainty for the item.  

Just as shown by the screenshot below, you can quickly find existing uncertainty by entering any word that show up in anywhere in the title of uncertainty.

Only the owner of note or site admin is allowed to change parent topic for the note, so you and site admin has the permission to access the tool for notes owned by you.

<img src="[CDN_HOST]/2889/434b805f-a959-4f28-a7f6-d7d465b4187f.png" title="parent-chooser-open.png" style="max-width:100%">

# How to Track Predictor Performance

SaveNowClub Notes allows you to track performance of any predictor by adding predictions as parts of note text and later validate them by adding facts as separate notes.

## Criteria of Predictions

For content that satisfy the following criteria, it can be classified as `Prediction` type of content:

1. predictions with clear target time frame: clear future target time point of predicted event
2. predictions that are checkable: clear prediction that can be checked by facts
3. predictions that matter: predicted event must matter to audience

Here is [an example](https://finance.creaders.net/2022/06/22/2497071.html) of prediction that does not meet our criteria: 

> 威尔森（Michael Wilson）在内的摩根士丹利策略师21日表示，标普500指数要跌到2,900点至3,100点，才会更加完全反映在经济衰退期间典型的企业获利萎缩。大摩策略师群表示：“目前看来，根据联准会陷入的通膨处境，经济衰退不再只是个尾部风险。”

The reason for not meeting our criteria is because it is a conditional statement of future scenario, cannot be proved as true or false by facts; also it is missing a clear target time frame.

## Our Approach Evaluating a Prediction

From perspectives of statistics and data, predictions of future events are in the forms of probability, this fact makes it hard to evaluate quality of a prediction since a historical event happens only once, you have no chance to calculate actual probability of an event and compare that with the predicted probability.

Instead, we use a simplified and a more straight-forward approach to evaluate prediction accuracy.  We view prediction as one non-random direction pointed out by predictors, after target time of predicted events has been reached, we compare actual fact against original prediction, if they match, then we rate the prediction as `hit`, otherwise, it's rated as `miss`.

# 如何使用时间线

时间线是一个基于网络的工具，它可以帮助您管理知识库，将您的书签和笔记整理为您关心的问题的答案。与其他书签网站（如 [Pinboard](https://pinboard.in/about/)、Instapaper 和 Pocket 等）一样，时间线会向您的浏览器添加一个 [小按钮](#如何使用书签小工具)，让您记住您阅读的内容，让您有机会用标签和描述性文字标记它们。

除了常见的书签网站功能外，SaveNowClub 时间线还提供以下独特功能：

* SaveNowClub 时间线允许您将书签和笔记（时间线项目）整理为问题的答案或主题下的帖子。时间线项目的数量比问题/主题的数量多得多，因为问题/主题相对较高，因为它们代表了您在特定时间关注的主要领域。除了使用主题标签外，您还可以通过查找其回答的问题或与之相关的主题来找到您保存的书签或笔记。用户使用 [归类选择器](#如何使用归类选择器) 工具管理时间线项目的主题。
* SaveNowClub 时间线允许您通过 [使用事实来验证预测](#how-to-track-predictor-performance) 查看预测器的跟踪记录。

# 如何使用书签小工具

SaveNowClub 使用书签小工具为网络内容添加书签。书签小工具是浏览器书签工具栏中的小型 JavaScript 链接。

以下是我们提供的书签小工具：<a href="javascript:q=location.href;if(document.getSelection){d=document.getSelection();}else{d='';};p=document.title;void(open('https://savenowclub.com/notes/submit?url=%27+encodeURIComponent(q)+%27&description=%27+encodeURIComponent(d)+%27&title=%27+encodeURIComponent(p),%27Pinboard%27,%27toolbar=no,width=550,height=400%27));">popup</a> 在您想要保存页面时打开一个小表单窗口。这是从 Web URL 添加内容的最快方法。

如何安装和使用书签小工具：如果您需要帮助来安装和/或使用我们的书签小工具，请参阅[本指南](https://www.howtogeek.com/189358/beginner-geek-how-to-use-bookmarklets-on-any-device/)。

## Android Chrome 上的书签小工具问题

此书签小工具已在 PC、Mac 和 iPhone 上的 Chrome 浏览器上进行了测试。在 Android 手机上的 Chrome 浏览器上，单击此书签小工具可能不会打开弹出表单，如果发生这种情况，请使用[本教程](https://paul.kinlan.me/use-bookmarklets-on-chrome-on-android/)中的方法解决该问题。

# 如何使用归类选择器

默认情况下，保存的时间线项目位于顶层。为其选择适当的不确定性是将时间线项目组织在适当主题下以供以后参考的好方法。您可以使用位于每个时间线项目页面上的“归类选择器”工具快速创建或选择项目的现有不确定性。

如下面的屏幕截图所示，您可以通过输入不确定性标题中任何地方出现的任何单词来快速找到现有的不确定性。

只有时间线项目所有者和站点管理员才允许更改时间线项目的父不确定性，因此您和站点管理员有权访问您拥有的时间线项目的工具。

<img src="[CDN_HOST]/2889/434b805f-a959-4f28-a7f6-d7d465b4187f.png" title="parent-chooser-open.png" style="max-width:100%">

# 如何跟踪预测器性能

SaveNowClub 时间线允许您通过将预测添加为时间线项目（书签或注释）的一部分来跟踪任何预测器的性能，然后通过将事实添加为单独的时间线项目来验证它们。

## 预测标准

对于满足以下条件的内容，可以将其归类为“预测”类型的内容：

1. 具有明确目标时间范围的预测：明确预测事件的未来目标时间点
2.可检验的预测：明确的预测，可以用事实来检验
3. 重要的预测：预测的事件必须对观众重要

这是不符合我们标准的预测的[示例](https://finance.creaders.net/2022/06/22/2497071.html)：

>威尔森（Michael Wilson）的摩根士丹利策略师21日表示，标普500指数要跌至2,900点至3,100点，才会更加反映在经济繁荣期间典型的企业利润萎缩。大摩策略师群表示：“目前看来，根据联准会的通膨增长，经济繁荣不再只是个尾部风险。”

不符合我们的标准的原因是因为它是对未来的条件陈述场景，无法用事实证明其真假；而且它缺少明确的目标时间框架。

## 我们评估预测的方法

从统计和数据的角度来看，对未来事件的预测是以概率的形式出现的，这一事实使得很难评估预测的质量，因为历史事件只发生一次，你没有机会计算事件的实际概率并将其与预测概率进行比较。

相反，我们使用一种简化且更直接的方法来评估预测准确性。我们将预测视为预测器指出的一个非随机方向，在达到预测事件的目标时间后，我们将实际情况与原始预测进行比较，如果它们匹配，则我们将预测评为`命中`，否则，将其评为`未命中`。