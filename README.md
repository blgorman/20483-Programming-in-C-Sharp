# 20483 Programming in C#.Net [.Net Framework 4.7 or 4.8]

This repo is forked from the official microsoft repo found [here](https://github.com/MicrosoftLearning/20483-Programming-in-C-Sharp)  

You should leverage the repository as long as it is available.  The course is no longer actively offered and the certification that goes with that exam is officially retired at the moment.

>**Note:** Since this code runs on the older .Net framework, it will not run on a Mac or Linux.  You must use a windows machine with .Net Framework 4.7 or 4.8 to get this code to run successfully.

## Using this repository

If you decided to use this repository to learn, the easiest thing for you to do would be to start by just cloning their repository to your local machine.  There really is no need to fork it unless you want to make a lot of changes and push those changes to your own version.

If you really want your own copy in your own github, then start by [forking the Microsoft repository](https://github.com/MicrosoftLearning/20483-Programming-in-C-Sharp).  

>**Note:** Don't fork mine, fork theirs. I might add stuff to this or remove stuff or modify it in ways that would deviate or make no sense to the original plan, or for you.  Also, if they do update it, I won't likely have those, at least not right away.

Either way, after cloning to your local machine, you have your own copy that you can use on your own machine. 

## Notes

With your own copy, note that you will need the following to make the repository code work on your machine:

1. Visual Studio 2022 [latest edition]

    Just because the code is older does not mean you need an older version of Visual studio.  Download and install the [latest Visual Studio Community Edition](https://visualstudio.microsoft.com/vs/).

1. .Net Framework 4.7 or 4.8
    
    You can get these by selecting them during installation of Visual Studio.  If you didn't select them, run the installer again and select the option for the .Net Framework 4.7 or 4.8.  You can find this under the ASP.Net installation section.  

1. SQL Server

    [Get yourself a copy of Sql Server developer edition to work locally on your machine](https://www.microsoft.com/en-us/sql-server/sql-server-downloads).  If you are short on resources, get the SQL Express edition.  Just note that using SQLExpress could mean default database connections need to be modified.  

1. Using the code

    Once you have everything installed, ensure that you set up the original database by double-clicking on the `SetupSchoolDB.cmd` file.  You should only have to do this once, and it will restore the database with two tables, which you can then leverage from code.

    Open `Mod01\Labfiles\Starter\Exercise 1\` folder and double click the solution file `School.sln` to automatically start Visual Studio.

    When it has completed opening, ensure you can build the project using `ctrl + shift + b`.  Once the build completes, you should see the form appear in the XAML designer window.  If not, you likely don't have the right version of the .Net Framework (This is **not** a .Net Core project!).  

## Up and Running

Once you are up and running, use the lab guides in the `Instructions` folder to walk through the labs for this course.
