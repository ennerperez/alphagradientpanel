![logo](https://raw.githubusercontent.com/ennerperez/alphagradientpanel/master/.editoricon.png)

# AlphaGradientPanel

A panel that has rounded borders, gradients, and transparency.

Original article can be found at [http://www.codeproject.com/Articles/13558/AlphaGradientPanel-an-extended-panel](http://www.codeproject.com/Articles/13558/AlphaGradientPanel-an-extended-panel))

All credits are for [Nicolas Walti](http://www.codeproject.com/script/Membership/View.aspx?mid=316374), I decided to place it in GitHub to make a NuGet package, because is the second most useful control in Windows Forms to me.

// Nicolas Walti thanks so much. Since 2006.

[![Build status](https://ci.appveyor.com/api/projects/status/wxt0ch5qb3f8412m?svg=true)](https://ci.appveyor.com/project/ennerperez/alphagradientpanel)
[![NuGet](http://img.shields.io/nuget/v/alphagradientpanel.svg)](https://www.nuget.org/packages/alphagradientpanel/)

---------------------------------------

See the [changelog](CHANGELOG.md) for changes.

## Table of contents

* [Implementing](#implementing)
* [Introduction](#introduction)
* [Features](#Features)
* [License](#license)

### Implementing

**Add the library to your project**

Add the [NuGet Package](https://www.nuget.org/packages/alphagradientpanel/). Right click on your project and click 'Manage NuGet Packages...'. Search for 'alphagradientpanel' and click on install. Once installed the library will be included in your project references. (Or install it through the package manager console: PM> Install-Package alphagradientpanel).

### Introduction
This is a panel, first of all. Therefore, it has all the advantages of a panel, plus some nice little features.

You'll just have to include the component in your toolbox and use it.

The only property that is a bit special is the Colors() property. It is a collection of items and has design-time visibility in the property grid. I'm still trying to achieve transforming the color name that appears in the property grid in a nice drawing... If anybody knows how that can be achieved, please, please, please, let me know 

### Features 
- Rounded corners (any one of them or all at the same time).
- Gradients (from 2 to n colors, with some special effects).
- Transparency (any color can be made transparent with an "Alpha" value between 0 and 255).
- Borders, even with rounded corners, have a nice little border.
- Image inclusion (position, opacity, size, grayscale, and padding).
- Padding of the content, of the back, and of the docking.

### License
This article, along with any associated source code and files, is licensed under [The Code Project Open License (CPOL)](LICENSE)