# Blazor United: The future of ASP.NET
## Description
In November we expect .NET 8 to release and ASP.NET Core 8 with it. One of the major advancements is a set of features that were first previewed to the world as "Blazor United". This set of features makes Blazor a "Full Stack" framework equally ready for SPA development and Server Side development as well as the spectrum in between.

This talk will go over the new features of ASP.NET 8, which actually benefit all ASP.NET developers whether you intend to use Blazor as a framework or not. You might find that you want to stick with the ASP.NET framework you are using but want to do some light modularization with components. Maybe you want to keep using your current SPA framework and use components.

# ASP.NET Core's UI Framework history

# ASP.NET Core Blazor hosting models
https://learn.microsoft.com/en-us/aspnet/core/blazor/hosting-models?view=aspnetcore-8.0

Blazor is a component based framework that received a lot of attention for being a client-side-rendered approach using WebAssembly.  Plenty of people seemed to think Blazor WAS WebAssembly.

Note the matrix on this page:
https://learn.microsoft.com/en-us/aspnet/core/blazor/hosting-models?view=aspnetcore-8.0#which-blazor-hosting-model-should-i-choose
"A component's hosting model is set by its render mode, either at compile time or runtime"

Note the various factors to consider in each hosting model.

Then note what it said for .NET 7.0
https://learn.microsoft.com/en-us/aspnet/core/blazor/hosting-models?view=aspnetcore-7.0#which-blazor-hosting-model-should-i-choose
"Select the Blazor hosting model based on the app's feature requirements."

