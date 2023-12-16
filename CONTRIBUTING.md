
# Report an Issue

Help us make AngularEditor better! If you think you might have found a bug, or some other weirdness, start by making sure
it hasn't already been reported. You can [search through existing @josipv/angular-editor-k2 issues](https://github.com/jvinkovic/angular-editor-k2/issues)
to see if someone's reported one similar to yours.

If not, then [create a plunkr](http://bit.ly/UIR-Plunk) that demonstrates the problem (try to use as little code
as possible: the more minimalist, the faster we can debug it).

Next, [create a new issue](https://github.com/jvinkovic/angular-editor-k2/issues/new) that briefly explains the problem,
and provides a bit of background as to the circumstances that triggered it. Don't forget to include the link to
that plunkr you created!

**Note**: If you're unsure how a feature is used, or are encountering some unexpected behavior that you aren't sure
is a bug, it's best to talk it out on
[StackOverflow](http://stackoverflow.com/questions/ask?tags=angular,@kolkov/angular-editor,@josipv/angular-editor-k2) before reporting it. This
keeps development streamlined, and helps us focus on building great software.


Issues only! |
-------------|
Please keep in mind that the issue tracker is for *issues*. Please do *not* post an issue if you need help or support. Instead, use StackOverflow. |

# Contribute


# Developing

`angular-editor` uses <code>Angular cli</code>, <code>npm</code> and <code>webpack</code>.

## Fetch the source code

The code for `angular-editor` is :

* [AngularEditor](https://github.com/jvinkovic/angular-editor-k2) (`@josipv/angular-editor-k2` on npm)

Clone repository.

```
mkdir angular-editor
cd angular-editor
git clone https://github.com/jvinkovic/angular-editor-k2.git
```

## Install dependencies

Use `npm` to install the development dependencies for the repository.

```
cd angular-editor
npm install
```


## Develop

* `npm run build and watch angular-editor`: Continuously builds the `@josipv/angular-editor-k2` code when sources change.
* `npm run start`: Continuously builds and runs Demo app when source or tests change.
