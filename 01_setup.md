# 01 Setup

## Prerequisites
The following are recommended tools for your development workflow. There may be alternatives but this should get you up and going.

- **SublimeText** - Text editor
- **iTerm** - Terminal/Command line
- **Git** - Version control

## Setup
In a terminal window, create a new directory and navigate into said directory.


```
mkdir training && cd $_
```

Use git to set up initial project. 

```
git init
```

Each new phase and track will be branches of this repository so that you can easily go back to see what state your project was in at the time. Feature format should look like this:

```
feature/cms-3
```

Where the pattern is `feature/\<dimension>-\<phase>`

So, assuming you are starting with the Front-end Track, run:

```
git branch feature/front-end-1
```

Now you're ready to get to going with your track.