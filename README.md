## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/friendraf/friendraf.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

<%@ Page Language="C#" AutoEventWireup="true" CodeFile="index.aspx.cs" Inherits="CS" %>

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title></title>
   <link href="main.css" rel="stylesheet" type="text/css" /> 
</head>
<body>
<form id="form1" runat="server">
    
<div class="container">
  <div class="header"><h1>check your password </h1>
    
      <div id="nav">
          <! -->
          <%		   
          Response.Write(DateTime.Now.ToString());
        %>
     </div>  
  </div>
  
  <div class="content">
      
      <asp:Panel ID="panel1" runat="server" Wrap="true" Visible="true">
      <h3>make your choice </h3>
      <asp:Button id="btnSubmit1" onclick="btnSubmit_old_user" runat="server" Text="enter password"></asp:Button>
      
       </asp:Panel>    
         
          
       <asp:Panel ID="old_user" runat="server" Wrap="true" Visible="false">   
       <h4> user name</h4>
        <asp:TextBox ID="username" MaxLength="20" runat="server" required="required"  />
          
      <h4> password</h4>
        <asp:TextBox ID="password" MaxLength="20" runat="server" required="required"  />
         <asp:Button id="btnSubmit3" onclick="btnSubmit_check_user" runat="server" Text="enter">
              </asp:Button>
      </asp:Panel>
         
       
      
      <asp:Panel ID="panel_tryagain" runat="server" Wrap="true" Visible="false">    
        <h1> user name or pasword did not match</h1>
           <asp:Button id="btnSubmit4" onclick="btnSubmit_return" runat="server" Text="press to try again">
              </asp:Button>
    
        </asp:Panel> 
      
  <asp:Panel ID="panel_good" runat="server" Wrap="true" Visible="false">    
        <h1> you match you may continue</h1>
          
        </asp:Panel> 
       <asp:Panel ID="panel_db" runat="server" Wrap="true" Visible="false">    
        <asp:label id="lblInfo" runat="server" Height="128px" Width="464px" Font-Size="Small" Font-     Names="Verdana" ForeColor="Maroon"></asp:label>
        </asp:Panel>       
            
            
        
      
     
      
    </div>
    <!-- end .content --></div>
  <div class="sidebar2">
    <h3>this is were your 3 adds will go</h3>
      <table>
      <tr> <td>add # 1</td></tr>
      <tr> <td>add #2</td></tr>
      <tr> <td>add #3</td></tr>
      </table>
      <!-- end .sidebar2 --></div>
  <div class="footer">
    <p>This is the area for the footer currently nothing will go in this spot delete the text but leave the space of later information.</p>
    <!-- end .footer --></div>
  <!-- end .container --></div>

    
</form>
</body>
</html>


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/friendraf/friendraf.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
