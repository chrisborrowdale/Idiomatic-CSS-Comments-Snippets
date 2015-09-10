Idiomatic CSS Comments for Sublime Text
=============================================

Idiomatic CSS style comments for Sublime Text.  Comment format based on [Idiomatic CSS](https://github.com/necolas/idiomatic-css) by [@necolas](https://github.com/necolas).

## Install

You can install via the Sublime Text Package Control (http://wbond.net/sublime_packages/package_control) and search for Idiomatic CSS Comments.

## Usage

There are several shortcuts for the different comment blocks.

### Basic Comment
Enter the shortcut `com-basic` followed by the `tab` key

``` css
/* This is a basic comment */
```

### Section Comment

Enter the shortcut `com-section` followed by the `tab` key

``` css
/* ==========================================================================
   This is a Section Comment
   ========================================================================== */
```

### Sub-Section Comment

Enter the shortcut `com-sub` followed by the `tab` key

``` css
/*
   This is a sub-section comment
   ========================================================================== */
```

### Long Comment

Enter the shortcut `com-long` followed by the `tab` key

``` css
/**
 * Short description using Doxygen-style comment format
 *
 * The first sentence of the long description starts here and continues on this
 * line for a while finally concluding here at the end of this paragraph.
 *
 * The long description is ideal for more detailed explanations and
 * documentation. It can include example HTML, URLs, or any other information
 * that is deemed necessary or useful.
 *
 * @tag This is a tag named 'tag'
 *
 * TODO: This is a todo statement that describes an atomic task to be completed
 *   at a later date. It wraps after 80 characters and following lines are
 *   indented by 2 spaces.
 */
```

### Todo List Comment
Enter the shortcut `com-todo` followed by the `tab` key	

``` css
/**
 * TODO:
 *
 * => Write some code
 * => Make some lists
 *
 */

---

## Sass-style Comments

Each of the comment-types listed above can be rendered in the form of a Sass-style comment using the shortcuts listed below.

* Basic Comment (Sass) - `scom-basic`
* Section Comment (Sass) - `scom-section`
* Sub-Section Comment (Sass) - `scom-sub`
* Long Comment (Sass) - `scom-long`
* Todo List Comment (Sass) - `scom-todo`

As before, each shortcut should be followed by the `tab` key.
