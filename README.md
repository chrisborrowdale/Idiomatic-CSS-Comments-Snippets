Idiomatic CSS Style Comments for Sublime Text
=============================================

Idiomatic CSS style comments for Sublime Text.  Comment format based on Idiomatic CSS by Nicolas Gallagher (https://github.com/necolas/idiomatic-css)

## Install

You can install via the Sublime Text Package Control (http://wbond.net/sublime_packages/package_control) and search for Idiomatic CSS Comments.

## Usage

There are several shortcuts for the different comment blocks.

### Basic Comment

	/* This is a basic comment */

#### Basic Comment Usage

Enter the shortcut `com-basic` followed by the `tab` key

### Section Comment

	/* ==========================================================================
   	   This is a Section Comment
       ========================================================================== */

#### Section Comment Usage

Enter the shortcut `com-section` followed by the `tab` key

### Sub-Section Comment

  /*
		 This is a sub-section comment
     ========================================================================== */

#### Sub Section Comment Usage

Enter the shortcut `com-sub` followed by the `tab` key

### Long Comment

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

#### Long Comment Usage

Enter the shortcut `com-long` followed by the `tab` key

### Todo List Comment

	/**
	 * TODO:
	 *
	 * => Write some code
	 * => Make some lists
	 *
	 */

#### Todo List Comment Usage

Enter the shortcut `com-todo` followed by the `tab` key
