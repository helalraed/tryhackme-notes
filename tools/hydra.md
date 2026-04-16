# 🔐 Hydra - Dictionary Attack

## 📌 Command Example

```bash id="1p0v8t"
hydra -l admin -P passlist.txt www.onlineshop.thm http-post-form "/login:username=^USER^&password=^PASS^:F=incorrect" -V
```

---

## 🧠 Explanation

* **hydra** → Tool used for brute-force attacks
* **-l admin** → Username
* **-P passlist.txt** → Password list
* **[www.onlineshop.thm](http://www.onlineshop.thm)** → Target website
* **http-post-form** → Type of login form
* **^USER^ / ^PASS^** → Placeholders
* **F=incorrect** → Failure message
* **-V** → Verbose output

---

## 💡 Notes

* Used for password guessing attacks
* Works on many protocols (HTTP, SSH, FTP)
* Always requires permission (legal testing only)
