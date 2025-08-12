# 🛠️ ESSENTIAL TOOLS QUICK REFERENCE
**Top 15 most used tools from 70+**
**For full list:** See jean-claude-tools-protocol-v1.md in archive

---

## 🔥 КРИТИЧЕСКИ ВАЖНЫЕ:

### **GitHub (через Zapier):**
```javascript
// AUTOSAVE - самый важный!
Zapier:github_create_or_update_file
- repo, path, content, message

// Поиск репо
Zapier:github_find_repository
- owner, repo
```

### **Google Drive:**
```javascript
// Поиск файлов
Zapier:google_drive_find_a_file
- title, drive, folder
```

### **Gmail:**
```javascript
// Поиск писем
Zapier:gmail_find_email
- query: "from:boris subject:ISKRA"

// Отправка
Zapier:gmail_send_email
- to, subject, body
```

---

## ⚡ NATIVE CLAUDE TOOLS:

```javascript
// Поиск в интернете
web_search
- query

// Загрузка URL
web_fetch
- url

// JavaScript анализ
repl
- code

// Создание контента
artifacts
- type, content
```

---

## 🎯 ГЛАВНЫЕ WORKFLOWS:

### **Autosave каждые 5 минут:**
```javascript
Zapier:github_create_or_update_file
repo: "guannko/Annoris"
path: "autosaves/jean-claude-autosave-YYYYMMDD-HHMM.md"
content: markdown
message: "autosave: description"
```

### **Проверка доступа:**
```javascript
Zapier:github_find_repository
owner: "guannko"
repo: "название"
```

---

## ⚠️ REMEMBER:
- У Jean ЕСТЬ прямой GitHub access!
- НЕ говори "нет доступа" без проверки
- Autosave в Annoris, НЕ в EYES!

---

*Compressed from 70+ tools to essential 15*