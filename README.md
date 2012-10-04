# Sublime Text 2 User Settings

* Mostly key bindings for Vintage Command Mode.
* Sublime Text 2 build 2220.
* Mac OSX Mountain Lion.

## Key Bindings

#### Normal

<table>
  <tr>
    <th>Key Binding</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>ctrl + ⌘ + r</code></td>
    <td>Reveal in sidebar</td>
  </tr>
  <tr>
    <td><code>shift + ⌘ + c</code></td>
    <td>Copy to Clipboard</td>
  </tr>
  <tr>
    <td><code>⌘ + v</code></td>
    <td>Paste and Indent</td>
  </tr>
  <tr>
    <td><code>alt + ⌘ + ]</code></td>
    <td>Reindent</td>
  </tr>
  <tr>
    <td><code>shift + ⌘ + t</code></td>
    <td>Run All Ruby Test file</td>
  </tr>
</table>

#### Vintage (Vim)

<table>
  <tr>
    <th>Key Binding</th>
    <th>Description</th>
  </tr>
  <tr>
    <th colspan="2">General</th>
  </tr>
  <tr>
    <td><code>,h</code></td>
    <td>The <code>Esc</code> substitute.</td>
  </tr>
  <tr>
    <td><code>,p</code></td>
    <td>Go to anything (use <code>@</code> for getting into symbols)</td>
  </tr>
  <tr>
    <td><code>,n</code></td>
    <td>Advanced New File</td>
  </tr>
  <tr>
    <td><code>,g</code></td>
    <td>Go to Line</td>
  </tr>
  <tr>
    <th colspan="2">Windows/Layout</th>
  </tr>
  <tr>
    <td><code>,u</code></td>
    <td>Single Layout</td>
  </tr>
  <tr>
    <td><code>,i</code></td>
    <td>Split or Columns: 2 Layout</td>
  </tr>
  <tr>
    <td><code>alt + ←</code></td>
    <td>Make Left Column 2/3 wide</td>
  </tr>
  <tr>
    <td><code>alt + → </code></td>
    <td>Make Right Column 2/3 wide</td>
  </tr>
  <tr>
    <td><code>ctrl + h</code></td>
    <td>Go to left column (Previous view)</td>
  </tr>
 <tr>
   <td><code>ctrl + l</code></td>
   <td>Go to right column (Next view)</td>
 </tr>
  <tr>
    <th colspan="2">Rails</th>
  </tr>
  <tr>
    <td><code>,m</code></td>
    <td>List Rails Models</td>
  </tr>
  <tr>
    <td><code>,c</code></td>
    <td>List Rails Controllers</td>
  </tr>
  <tr>
    <td><code>,v</code></td>
    <td>List Rails Views</td>
  </tr>
  <tr>
    <td><code>,e</code></td>
    <td>List Rails Tests (Examples)</td>
  </tr>
  <tr>
    <th colspan="2">Ruby Test</th>
  </tr>
  <tr>
    <td><code>,v</code></td>
    <td>Toggles test and tested code in split view</td>
  </tr>
  <tr>
    <td><code>,.</code></td>
    <td>Toggles test and tested code</td>
  </tr>
  <tr>
    <td><code>,t</code></td>
    <td>Run Last Ruby Test file (No need to be in test file)</td>
  </tr>
  <tr>
    <td><code>,s</code></td>
    <td>Run Single Ruby Test file</td>
  </tr>
  <tr>
    <td><code>,r</code></td>
    <td>Run All Ruby Test file</td>
  </tr>
  <tr>
    <th colspan="2">Vintage Ex</th>
  </tr>
  <tr>
      <td>
          <code>:</code>
      </td>
      <td>Vim : awsomeness (w, q,...)</td>
  </tr>
</table>

## Settings (Preferences)

### Tab Size:

* Global: 4
* Ruby: 2

### Theme:

Soda Dark

### Color Scheme:

* Global - `Molokai-Black` (Normal Molokai with chaged background to pure black + Git Annotations colors).
* Markdown - `Sunburst`

### Set to true:

* ensure_newline_at_eof_on_save
* highlight_modified_tabs
* translate_tabs_to_spaces
* trim_trailing_white_space_on_save
* vintage_start_in_command_mode
* indent_to_bracket
* highlight_line

### Rulers

85 lines

## Plugin Packages


* AdvancedNewFile
* CTags
* Git
* Package Control
* RailsCasts Colour Scheme
* RSpec
* RSpec (snippets and syntax)
* Ruby 1.9 Hash Converter
* RubyTest
* SCSS
* Simple Rails Navigator
* SublimeLinter
* Theme - Soda
* VintageEx
* ZenCoding
