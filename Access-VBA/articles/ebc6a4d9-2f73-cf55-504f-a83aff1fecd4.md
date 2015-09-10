
# Form.GridX Property (Access)

 **Last modified:** July 28, 2015

You can use the  **GridX** property (along with the **GridY** property) to specify the horizontal and vertical divisions of the alignment grid in form Design view. Read/write **Integer**.

## Syntax

 _expression_. **GridX**

 _expression_A variable that represents a  **Form** object.


## Remarks

Enter an integer between 1 and 64 representing the number of subdivisions per unit of measurement. If the  **Measurement system** box is set to U.S. on the **Numbers** tab of the **Regional Options** dialog box of Windows Control Panel, the default setting is 24 for the **GridX** property (horizontal) and 24 for the **GridY** property (vertical).

In Visual Basic, you set this property by using a numeric expression.

The  **GridX** and **GridY** properties provide control over the placement and alignment of objects on a form or report. You can adjust the grid for greater or lesser precision. To see the grid, click **Grid** on the **View** menu. If the setting for either the **GridX** or **GridY** properties is greater than 24, the grid points disappear from view (although the grid lines are still displayed).


## See also


#### Concepts


 [Form Object](72ef9219-142b-b690-b696-3eba9a5d4522.md)
#### Other resources


 [Form Object Members](e1976b58-28ca-8f76-cdf3-6732cb06ce6c.md)