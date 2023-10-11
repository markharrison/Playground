# GitHub Copilot Demo

## Create an API app

Create an empty directory.  With VSCode open the directory.

``` 
I am using .NET 8.0
I want to create a single API app.
I also need a MSTest unit test project.
What are the dotnet commands to scaffold a solution.  The files should be called "Color".
```

Run commands.  Open Solution - use F1 `.NET Open Solution` .   Add project reference from Test to API

Open `Program.cs` - remove Route & Model

```
create colors model called ColorModel to include a name and hexcode.
```
Insert code 
```
create two API routes.
First - an API to return all colors.   Intialise with 3 colors - "red", "yellow", "black"
Sencond - an API to insert a new color.
I am using .NET 8.0  minimal APIs.

```
Insert code .   Create new default data.
```
i want a new static class called ColorUtilities.
```
Create `ColorUtilities.cs` and add code 

```
I want a validateHexCode function using Regex - add to static class  ColorUtilities.
```
```
// function to test for shade of red
```
```
add hexcode validation
```

Fix Bug / make resilient.

```
write a unit test using MSTEST to validate the ColorUtilities.ValidateHexCode function.  i need to test all scenerios / edge cases / errors
```

```
separate into different tests 
```

```
explain this code
```

```
Add function to add two numbers 
Divide - make resilient
```

Animal class
Dog class 
Make Sound

Languages 

convert Vue 2 to Vue 3






