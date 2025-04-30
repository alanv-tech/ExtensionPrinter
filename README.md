# ⚠️ NOTE

ExtensionPrinter is officially deprecated after 3 months and 17 days. Thank you for using it

---

# 🔷 About The Exploit

**Extension Printer** is an exploit that serves as the **successor to the Extension Hanger**.
It works by generating and printing out **thousands of embedded web applications (iFrames)**, which causes the RAM usage for a webpage or extension to exceed the usage limit. This ultimately causes the extension to crash. It is similar to the LTMEAT exploit which uses the same method to kill an extension.

> **💡 Tip:** Disabling the **V8 optimizer** can significantly reduce lag.  
> However, **this feature is not available on Chromebooks running the older version**.  

### 🌐 Website  

If you arrived here from GitHub pages website, **[click here](https://github.com/alanv-tech/ExtensionPrinter)**.  

## 📜 **Copy This Code** 
Copy and paste the following code into your browser’s URL bar. Click anywhere on the gray screen, and a popup should appear prompting you to enter a password. The password is **"blobbyboi"**. Click "submit" and it should open up the instructions and the exploit page.

```
data:text/html;charset=utf-8,%3C!DOCTYPE%20html%3E%0A%3Chtml%20lang%3D%22en%22%3E%0A%3Chead%3E%0A%20%20%20%20%3Cmeta%20charset%3D%22UTF-8%22%3E%0A%20%20%20%20%3Cmeta%20name%3D%22viewport%22%20content%3D%22width%3Ddevice-width%2C%20initial-scale%3D1.0%22%3E%0A%20%20%20%20%3Ctitle%3EPassword%20Protected%20Button%3C%2Ftitle%3E%0A%20%20%20%20%3Cstyle%3E%0A%20%20%20%20%20%20%20%20%2F*%20Style%20the%20button%20to%20take%20up%20the%20whole%20screen%20*%2F%0A%20%20%20%20%20%20%20%20%23fullscreenButton%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20position%3A%20fixed%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20top%3A%200%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20left%3A%200%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20width%3A%20100%25%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20height%3A%20100%25%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20background-color%3A%20rgba(0%2C%200%2C%200%2C%200.5)%3B%20%2F*%20Slightly%20transparent%20background%20*%2F%0A%20%20%20%20%20%20%20%20%20%20%20%20color%3A%20white%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20font-size%3A%202rem%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20border%3A%20none%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20cursor%3A%20pointer%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20z-index%3A%201000%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20%2F*%20Style%20the%20password%20input%20modal%20*%2F%0A%20%20%20%20%20%20%20%20%23passwordModal%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20display%3A%20none%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20position%3A%20fixed%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20top%3A%2050%25%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20left%3A%2050%25%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20transform%3A%20translate(-50%25%2C%20-50%25)%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20padding%3A%2020px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20background-color%3A%20rgba(0%2C%200%2C%200%2C%200.8)%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20color%3A%20white%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20border-radius%3A%2010px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20z-index%3A%201100%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20%23passwordInput%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20padding%3A%2010px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20font-size%3A%201rem%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20margin-bottom%3A%2010px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20border-radius%3A%205px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20border%3A%201px%20solid%20%23fff%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20%23passwordSubmit%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20padding%3A%2010px%2020px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20font-size%3A%201rem%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20background-color%3A%20%2328a745%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20border%3A%20none%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20color%3A%20white%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20border-radius%3A%205px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20cursor%3A%20pointer%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20%23passwordSubmit%3Ahover%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20background-color%3A%20%23218838%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20%23errorMessage%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20color%3A%20red%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20font-size%3A%201rem%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20margin-top%3A%2010px%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20display%3A%20none%3B%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%3C%2Fstyle%3E%0A%3C%2Fhead%3E%0A%3Cbody%3E%0A%0A%20%20%20%20%3C!--%20Button%20that%20covers%20the%20whole%20screen%20with%20text%20--%3E%0A%20%20%20%20%3Cbutton%20id%3D%22fullscreenButton%22%20onclick%3D%22showPasswordModal()%22%3EClick%20here%20to%20enter%20password%3C%2Fbutton%3E%0A%0A%20%20%20%20%3C!--%20Password%20input%20modal%20--%3E%0A%20%20%20%20%3Cdiv%20id%3D%22passwordModal%22%3E%0A%20%20%20%20%20%20%20%20%3Ch2%3EPlease%20enter%20the%20password%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%3Cinput%20type%3D%22password%22%20id%3D%22passwordInput%22%20placeholder%3D%22Password%22%20%2F%3E%0A%20%20%20%20%20%20%20%20%3Cbr%3E%0A%20%20%20%20%20%20%20%20%3Cbutton%20id%3D%22passwordSubmit%22%20onclick%3D%22checkPassword()%22%3ESubmit%3C%2Fbutton%3E%0A%20%20%20%20%20%20%20%20%3Cp%20id%3D%22errorMessage%22%3EIncorrect%20password.%20Please%20try%20again.%3C%2Fp%3E%0A%20%20%20%20%3C%2Fdiv%3E%0A%0A%20%20%20%20%3Cscript%3E%0A%20%20%20%20%20%20%20%20const%20correctPassword%20%3D%20'blobbyboi'%3B%20%2F%2F%20Set%20your%20password%20here%0A%0A%20%20%20%20%20%20%20%20%2F%2F%20Function%20to%20show%20the%20password%20modal%0A%20%20%20%20%20%20%20%20function%20showPasswordModal()%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20document.getElementById('passwordModal').style.display%20%3D%20'block'%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20%2F%2F%20Function%20that%20checks%20the%20password%20and%20opens%20the%20pages%0A%20%20%20%20%20%20%20%20function%20checkPassword()%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20const%20userPassword%20%3D%20document.getElementById('passwordInput').value%3B%0A%0A%20%20%20%20%20%20%20%20%20%20%20%20if%20(userPassword%20%3D%3D%3D%20correctPassword)%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20Open%20both%20URLs%20in%20new%20tabs%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20window.open('https%3A%2F%2Fextprint3r.github.io%2Fprinter.html'%2C%20'_blank')%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20window.open('https%3A%2F%2Fgithub.com%2Falanv-tech%2FExtensionPrinter%2Fwiki%2FTHE-EXPLOIT'%2C%20'_blank')%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20Optionally%2C%20redirect%20the%20current%20window%20to%20one%20of%20the%20URLs%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20window.location.replace(%22https%3A%2F%2Fgithub.com%2Falanv-tech%2FExtensionPrinter%2Fwiki%2FTHE-EXPLOIT%22)%3B%0A%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20Hide%20the%20modal%20after%20successful%20password%20input%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20document.getElementById('passwordModal').style.display%20%3D%20'none'%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20Show%20error%20message%20and%20close%20the%20tab%20after%20a%20delay%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20document.getElementById('errorMessage').style.display%20%3D%20'block'%3B%0A%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20Set%20a%20delay%20before%20closing%20the%20tab%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20setTimeout(()%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20window.close()%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%2C%203000)%3B%20%2F%2F%20Close%20the%20tab%20after%203%20seconds%0A%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%3C%2Fscript%3E%0A%0A%3C%2Fbody%3E%0A%3C%2Fhtml%3E
```

## 📌 Changelog  
To view the full changelog, **[click here](https://github.com/alanv-tech/ExtensionPrinter/blob/main/CHANGES.md)**.  

---

# ❓ Need Help?  
If you need assistance:  
- Check the **troubleshooting section** in the wiki.  
- Submit an **issue** if you encounter a problem.  

We're here to help! 🚀  

## Frequently Asked Questions
- Is it permanent? No, it is not. You'll have to do it every time you open your Chromebook.
- Are the steps quick and easy? Not really, but we are trying to make it as simple as possible.
- Will it lag my computer? It depends on the computer, but most of the time no.
- Can I play games after using it? Yes, any site that is blocked by an extension will work now.

---

**Credit to Blobby Boi for the original code and idea**
