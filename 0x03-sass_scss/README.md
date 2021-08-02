# 0x03. Sass & Scss

This project is to understand and use SASS & Scss

## What Sass means
syntactically awesome style sheets

## How to write Sass & Scss file
- Indented syntax or SASS: It uses indentation rather than brackets and newlines. The files use the SASS extension.
- Sassy CSS or SCSS: It is the superset of CSS3. Its files use the SCSS extension. Every valid CSS is the valid SCSS.

## What is the difference between Sass and Scss
SASS (Syntactically Awesome Style Sheets) is a pre-processor scripting language that will be compiled or interpreted into CSS. SassScript is itself a scripting language whereas SCSS is the main syntax for the SASS which builds on top of the existing CSS syntax.

## What is the Sass preprocessing
CSS on its own can be fun, but stylesheets are getting larger, more complex, and harder to maintain. This is where a preprocessor can help. Sass has features that don't exist in CSS yet like nesting, mixins, inheritance, and other nifty goodies that help you write robust, maintainable CSS.

## How to declare a variable
Sass uses the $ symbol to make something a variable

## How to use nested definition
Sass will let you nest your CSS selectors in a way that follows the same visual hierarchy of HTML. Be aware that overly nested rules will result in over-qualified CSS that could prove hard to maintain and is generally considered bad practice.

## How to import a Sass file
Sass imports have the same syntax as CSS imports, except that they allow multiple imports to be separated by commas rather than requiring each one to have its own @import. Also, in the indented syntax, imported URLs aren’t required to have quotes.

## How to use mixins
Mixins are defined using the @mixin at-rule, which is written @mixin <name> { ... } or @mixin name(<arguments...>) { ... }. A mixin’s name can be any Sass identifier, and it can contain any statement other than top-level statements. They can be used to encapsulate styles that can be dropped into a single style rule; they can contain style rules of their own that can be nested in other rules or included at the top level of the stylesheet; or they can just serve to modify variables.

## How to declare extend/inheritance styles
It’s written @extend <selector>, and it tells Sass that one selector should inherit the styles of another.

## How to manipulate operators
Sass supports a handful of useful operators for working with different values. These include the standard mathematical operators like + and *, as well as operators for various other types:

== and != are used to check if two values are the same.
+, -, *, /, and % have their usual mathematical meaning for numbers, with special behaviors for units that matches the use of units in scientific math.
<, <=, >, and >= check whether two numbers are greater or less than one another.
and, or, and not have the usual boolean behavior. Sass considers every value “true” except for false and null.
+, -, and / can be used to concatenate strings.

### Order of Operations
Sass has a pretty standard order of operations, from tightest to loosest:

The unary operators not, +, -, and /.
The *, /, and % operators.
The + and - operators.
The >, >=, < and <= operators.
The == and != operators.
The and operator.
The or operator.
The = operator, when it’s available.