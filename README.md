# AutoDoxygen
A fork of [jonimat](https://marketplace.visualstudio.com/items?itemName=jonimat.AutoDoxyDoc) plugin by AutoDoxyDoc

Generates Qt/JavaDoc style documentation comments for C/C++ when /** is typed.
AutoDoxygen modifies the code comment style based on AutoDoxyDoc, making it compatible with VSDoxyHighlighter for highlighted display.

Supports the following format:
<pre>
/**
 *  comment
 *
 *      @param param_name[direction] comment
 *
 *      @return comment
 *
 *      @remarks
 *      ...
 */
</pre>

Supports also smart updating of existing comments using Alt+D. Smart updating
can preserve existing comments but also add/remove parameter comments based on the changes
done to the function parameters.

AutoDoxyDoc also supports some customizations:
- Tag indentation level
- Tag style (JavaDoc or Qt)
- **Smart comments**: Autogeneration of comments based on the function information
- **Abbreviations**: Ability to unabbreviate word for smart comments

Icons made by [Vitaly Gorbachev](https://www.flaticon.com/free-icon/document_2301329) from [www.flaticon.com](https://www.flaticon.com/).
