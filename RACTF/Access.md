# Access

Viewing the source code of the site, the script located at the bottom of the page displays:

```
const USERNAME = "admin";
const PASSWORD = "*4eb?F$Z^}W;)tL^";
$("div").on("click", "#submit", () => {
	const username = $("#username").val();
	const password = $("#password").val();
	if (username === USERNAME && password === PASSWORD) {
		$("#error").hide();
		$("#flag").show();
	} else {
		$("#flag").hide();
		$("#error").show();
	}
});
```

The code reveals the username and password in lines 1 and 2.

---
Flag: `elite{WhatABadLoginPage!}`

