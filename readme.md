## What is Flutter?
It is a "tool" that allows you to build native cross-platform (iOS, Android) apps with one programming language and codebase.

## What is Dart?
It is a programming language which is focussed on building frontend user interfaces though it is not limited on mobile apps only. 

It is developed by Google

It is object oriented and strongly typed and its syntax is like a mixture of JavaScript, Java, C#


## Flutter Architecture
In flutter, everything is a widget including the whole page. So the entire app is built as a widget tree.

In flutter there are no drag & drop and there is no visual editor so we only code

There is one codebase and in you can have as many different dart files withing one project.

You can also choose to embrace the platform differences i.e

    child:  Theme.of(context).platform == TargetPaltform.iOS
        ? CupertinoButton(...) //Apple look & feel   
        : RaisedButton(...) // Material (Google) look & feel

By default flutter uses Material Design which is created and heavily used by Google.

Material Design is highly customizable and works on iOS devices too and it is built into Flutter but you can also find Apple-Styled (Cupertino) widgets

## Building Our App
Stateless widgets are immutable, meaning that their properties can't change—all values are final.

Stateful widgets maintain state that might change during the lifetime of the widget. Implementing a stateful widget requires at least two classes: 1) a StatefulWidget that creates an instance of a State class. The StatefulWidget object is, itself, immutable and can be thrown away and regenerated, but the State object persists over the lifetime of the widget.

