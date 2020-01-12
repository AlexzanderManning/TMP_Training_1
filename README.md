# TMP_Training_1
My take home challenge for TMP WorldWide.

the live version of the site is hosted at : https://alexzandertmpchallenge.netlify.com/


##Architecture
The layout of this app is using a the ITCSS arhcitecture. You can read about it here : https://cssguidelin.es/

The app is layed out this way to manage specificity for the long term and to keep it flat across the entire app, and maximize productivity of developers who are not familar with the code base.

Each component is written to be reusable across the entire site, and new compoents added should follow suit.

To find a where a particulaur piece of code or component is located you can easily find in the Table of Contents located in the main.scss file.



##Naming Conventions
This Project uses BEM like naming conventions. You can read about it here : http://getbem.com/naming/

The naming schemes follows some basic rules :

1. Each component or section gets its own class name called a block.

    Example:  .block

2. Each element within that block container is called is named with 2 underscores like :
    Example: .block__elementName
    Example 2: .block__btn
    
3. for classes modifying elements within a particular block the naming convention includes two dashes like so:
    example: .block__btn--blue    
    
    
##Adding Components
Each compnoent should be written following the guidelines above and should only be written using class selctors. 

ID selctors for components are frowned upon because they are over specific and lead to styling issues in the long run. 

When a new component is added please update the table of contents to reflect that so that another developer can easily get up to speed.  