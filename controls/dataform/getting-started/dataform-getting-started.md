---
title: Getting Started
page_title: Getting Started
position: 0
slug: dataform-getting-started
---

# Getting Started #

This example will guide you through the steps needed to add a basic **RadDataForm** control in your application.

>Before you proceed, please, take a look at these articles and follow the instructions to setup your app:

>- [Setup on Windows]({%slug getting-started-windows%})
>- [Setup on Mac]({%slug getting-started-mac%})

## Example

If your app is setup, you are ready to add a **RadDataForm** control.

Here is a sample class that will be the view model of the data form:

<snippet id='dataform-gettingstarted-source'/>

Here is the setup of the data form:

<snippet id='dataform-gettingstarted-setup-xaml'/>
<snippet id='dataform-gettingstarted-setup-csharp'/>

You also need to add the following namespace:

<snippet id='xmlns-telerikinput'/>
<snippet id='ns-telerikinput'/>

After that you have to specify the editor types:

<snippet id='dataform-gettingstarted-register-editors'/>

And finally set the data form as content of your page.

Here is the result:

![](../images/dataform-gettingstarted.png)
	
## See Also

- [DataForm Editors]({%slug dataform-editors%})
- [Project Wizard]({% slug project-wizard %})
- [Getting Started on Windows]({% slug getting-started-windows %})
- [Getting Started on Mac]({% slug getting-started-mac %})