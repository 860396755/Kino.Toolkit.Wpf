# Kino.Toolkit.Wpf

[![dotnet-version](https://img.shields.io/badge/.net-%3E%3D4.5-blue.svg?style=flat-square)](https://dotnet.microsoft.com/) [![nuget-version](https://img.shields.io/nuget/v/Kino.Toolkit.Wpf.svg?style=flat-square)](https://www.nuget.org/packages/Kino.Toolkit.Wpf/) [![MIT License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](https://github.com/DinoChan/Kino.Toolkit.Wpf/blob/master/LICENSE) [![IDE-version](https://img.shields.io/badge/IDE-vs2017-purple.svg?style=flat-square)](https://visualstudio.microsoft.com/) [![IDE-version](https://img.shields.io/badge/IDE-vs2019-purple.svg?style=flat-square)](https://visualstudio.microsoft.com/)


![](https://raw.githubusercontent.com/DinoChan/Kino.Toolkit.Wpf/master/demo.png)

Kino.Toolkit.Wpf是一组简单实用的WPF控件与工具，用于介绍自定义控件的入门。相关博客地址如下：


[开始一个自定义控件库项目](https://www.cnblogs.com/dino623/p/CustomControLibrary.html)

介绍开始一个自定义控件库项目需要考虑的地方，包括版本号、目录结构等。

[从ContentControl开始入门自定义控件](https://www.cnblogs.com/dino623/p/How-To-Create-CustomControl.html)

ContentControl是WPF中最基础的一种控件，Window、Button、ScrollViewer、Label、ListBoxItem等都继承自ContentControl。而且ContentControl的结构十分简单，很适合用来入门自定义控件。

这篇文章通过自定义一个ContentControl来介绍自定义控件的一些基础概念，包括自定义控件的基本步骤及其组成。

[了解如何自定义ItemsControl](https://www.cnblogs.com/dino623/p/Custom-ItemsControl.html)

WPF提供了一大堆ItemsControl的派生类：HeaderedItemsControl、TreeView、Menu、StatusBar、ListBox、ListView、ComboBox；而且配合Style或DataTemplate足以完成大部分的定制化工作。可以说ItemsControl是XAML系统灵活性的最佳代表。这篇文章介绍简单的自定义ItemsControl知识，通过重写GetContainerForItemOverride和IsItemItsOwnContainerOverride、PrepareContainerForItemOverride函数并使用ItemContainerGenerator等自定义一个简单的IItemsControl控件。

[自定义控件的代码如何与ControlTemplate交互](https://www.cnblogs.com/dino623/p/interact_with_ControlTemplate.html)

介绍自定义控件的代码如何和ControlTemplate交互，涉及的知识包括RelativeSource、Trigger、TemplatePart和VisualState，以及它们之间的选择。


[以Button为例谈谈如何模仿Aero2主题](https://www.cnblogs.com/dino623/p/Aero2Theme.html)

WPF控件库通常都会提供“素颜”的外观，这样做的最大好处是可以和原生控件或其它控件库兼容。这篇文章以Button为例，谈谈现在最常用的Aero2主题的设计元素，以及尺寸、颜色、字体、动画等细节。

[简单的表单布局控件](https://www.cnblogs.com/dino623/p/WPF-Form-Layout.html)

Form是一个轻量的表单布局控件，同时也是一个很好的结合了ItemsControl、ContentControl、附加属性的教学例子。


[让Form在加载后自动获得焦点](https://www.cnblogs.com/dino623/p/AutoFocus.html)

为了让Form可以在加载后自动获得焦点，我创建了一个叫FocusService的工具类，这篇文章介绍这个类的使用及原理，以及补充一些WPF焦点的知识。

[为Form和自定义Window添加FunctionBar](https://www.cnblogs.com/dino623/p/FunctionBar.html)

这篇文章介绍了另一种ItemsControl的实现方式，并使用它为Form及自定义Window添加常用的按钮及其它功能。



[Window(窗体)的UI元素及行为](https://www.cnblogs.com/dino623/p/uielements_of_window.html)

这篇文章主要讨论标准Window的UI元素和行为。无论是桌面编程还是日常使用，Window(窗体)都是最常接触的UI元素之一，既然Window这么重要那么多了解一些也没有坏处。

[使用WindowChrome自定义Window Style](https://www.cnblogs.com/dino623/p/custom_window_style_using_WindowChrome.html)

介绍使用WindowChrome自定义Window的原理及各种细节。

[使用WindowChrome的问题](https://www.cnblogs.com/dino623/p/problems_of_WindowChrome.html)

使用WindowChrome自定义Window会遇到很多问题，例如最大化的尺寸问题，这篇文章介绍如何处理这些细节。

[使用WindowChrome自定义RibbonWindow](https://www.cnblogs.com/dino623/p/custom_ribbonwindow_using_WindowChrome.html)

因为WPF原生的RibbonWindow有不少UI上的Bug，所以我提供了一个自定义的RibbonWindow以解决这些问题。



[排序、筛选以及高亮](https://www.cnblogs.com/dino623/p/sort_filter_highlight.html)

介绍WPF怎么做筛选及排序，以及使用自定义的附加属性实现文本高亮。



[使用TypeConverter强化文本高亮的功能](https://www.cnblogs.com/dino623/p/TextBlockHighlightSource.html)

这篇文章介绍了使用TypeConverter简化调用，以及继承自FrameworkElement以便使用Style。

[好用的VisualTreeExtensions](https://www.cnblogs.com/dino623/p/VisualTreeExtensions.html)

VisualTreeExtensions封装了`VisualTreeHelper`并提供了各种查询Visual Tree的方法，这篇文档介绍了这个工具类大致的内容，以及使用上要注意的地方。

[了解WPF的布局过程，并利用Measure为Expander添加动画](https://www.cnblogs.com/dino623/p/Resizer.html)

这篇文章介绍WPF UI元素的两步布局过程，并且通过Resizer控件介绍只使用Measure可以实现些什么内容。



[自定义Expander](https://www.cnblogs.com/dino623/p/Custom_Expander.html)

继续Measure的话题，这次真的创建了个自定义的Expander。




[给WPF一个HyperlinkButton](https://www.cnblogs.com/dino623/p/WPF_HyperlinkButton.html)

这篇文章的目的是介绍怎么在WPF里创建自定义的HyperlinkButton控件。



[关于ScrollViewr和滚动轮劫持(scroll-wheel-hijack)](https://www.cnblogs.com/dino623/p/scroll-wheel-hijack.html)

这篇文章介绍了如何自定义ScrollViewer以避免滚动轮劫持的问题。


[模仿UWP的ProgressRing](https://www.cnblogs.com/dino623/p/create_a_ProgressRing_for_wpf.html)

这篇文章介绍如何在WPF中模仿UWP的ProgressRing。

[创建包含CheckBox的ListBoxItem](https://www.cnblogs.com/dino623/p/Create_ListBoxIte_with_a_CheckBox.html)

介绍如何为ListBox和DataGrid添加用于选中项目的CheckBox。

[在MenuItem上使用RadioButton](https://www.cnblogs.com/dino623/p/Uising_RadioButton_in_MenuItem.html)

这篇文章将介绍如何自定义一个RadioButtonMenuItem控件实现MenuItem的单选功能。


[自定义一个“传统”的 Validation.ErrorTemplate](https://www.cnblogs.com/dino623/p/Validation_ErrorTemplate.html)

这篇文章介绍如何自定义一个模仿 Silverlight 的 Validation.ErrorTemplate，以便可以展示详细的错误信息。
