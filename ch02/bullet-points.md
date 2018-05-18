- The `Button` element is used to add a button.
- The `Spinner` element is used to add a spinner. A spinner is a drop-down list
  of values.
- All GUI components are types of view. They inherit from the Android View class.
- Add an array of string values using:
  ```
  <string-array name="array">
    <item>string1</item>
	...
  </string-array>
  ```
- Reference a `string-array` in the layout using: `"@array/array_name"
- Make a button call a method when clickeed by adding the following to the layout:
  ```
  android:onClick="clickMethod"
  ```
  There needs to be a corresponding method in the activity:
  ```
  public void clickMethod(View view) {
  }
  ```
- *R.java* is generated for you. It enables you to get references for layouts,
  GUI components, Strings, and other resources in your Java code.
- Use `findViewById()` to get a reference to a view.
- Use `setText()` to set the text in a view.
- Use `getSelectedItem()` to get the selected item in a spinner.
- Add a custom class to an Android project by going to File Menu --> New... -->
  Java Class.