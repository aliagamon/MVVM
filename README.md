# MVVM
Unity MVVM
A way of making unity UI more organized

This framework provides you a reactive way of making UIs using UniRx, and you can use this to seperate Logic and UI from each other.

This way you can have your logic written in normal C# code and this gives you the ability to easily write Test Cases and reusing logic in the server side for Input validation and Anti cheat strategies.

This framework is 100% async and it comes with Dependency Injection, Message Broker, Dialogue Service, Navigation Service for moving between scenes, Reactive Binding including One-way binding, Two-way binding, Event binding, Visibility binding and Collection binding which you can use converters to convert Input/Output values and all of this are done in editor without any code.

It's have Binding Debugger for debugging all these reactive binds in edit mode or playing.

It also have a Localization Service supporting both JSON and CSV files as translation table.

## How to install
### Git Submodule
If your project is a git repository easiest way to installing it is by submoduling, Go to root of your project and run these commands to clone this repository and all it's submodules in Assets/Scripts/MVVM directory and you are done.
```
git submodule add https://github.com/rzvxa/MVVM.git Assets/Scripts/MVVM
git submodule update --init --recursive
```
### Git Clone
If you don't like submoduling this repository then you can use this.
```
git clone https://github.com/rzvxa/MVVM.git Assets/Scripts/MVVM
cd Assets/Scripts/MVVM
git submodule update --init --recursive
```
## Dependencies
Here is a list of all Third-Party libs that i'm using for (Unity)MVVM framework make sure that you have all of them in place and reference them in assembely definition.
* DryIoc
* rotorz reorderable list
* UniRx
* UniTask
* Newtonsoft.Json

There is no documentation yet, But i've used this in quite a lot of commercial projects. I will add documentation later myself but any contribution is welcomed.
