
# Paragraph.Creator Property (Word)

Returns a 32-bit integer that indicates the application in which the specified object was created. Read-only  **Long**.


## Syntax

 _expression_. **Creator**

 _expression_Required. A variable that represents a  ** [Paragraph](0a704079-a082-4ab1-841b-fc0d49dd26d4.md)** object.


## Remarks

If the object was created in Microsoft Word, the  **Creator** property returns the hexadecimal number 4D535744, which represents the string "MSWD." This property was primarily designed to be used on the Macintosh, where each application has a four-character creator code. For example, Microsoft Word has the creator code MSWD. For additional information about this property, consult the language reference Help included with Microsoft Office Macintosh Edition.


## See also


#### Concepts


 [Paragraph Object](0a704079-a082-4ab1-841b-fc0d49dd26d4.md)
#### Other resources


 [Paragraph Object Members](e1fc5b91-e908-580e-ab72-898648a5c0c3.md)
