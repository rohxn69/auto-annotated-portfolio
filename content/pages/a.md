---
type: PageLayout
title: Help Rohaaaaan!
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: This in an empty page
    subtitle: The section subtitle
    text: |
      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Password Protected Page</title>
          <script>
              function checkPassword() {
                  const password = document.getElementById("password").value;
                  const correctPassword = "mypassword";  // Replace with your desired password

                  if (password === correctPassword) {
                      // Redirect to the protected page
                      window.location.href = "protected.html"; // Your protected page
                  } else {
                      alert("Incorrect password! Please try again.");
                  }
              }
          </script>
      </head>
      <body>
          <h2>Enter Password to Access Content</h2>
          <input type="password" id="password" placeholder="Enter Password">
          <button onclick="checkPassword()">Submit</button>
      </body>
      </html>
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
