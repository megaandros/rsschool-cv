#  🌟 MARIA AKULOVA

### 🚀 Junior Frontend Developer (React)

********

### 📇 Contacts:

 📞 **Phone:**  `+38 095 7838840`  
 ✉️ **Email:**  [megaandros@gmail.com](mailto:megaandros@gmail.com)  
📱 **Telegram:** [@MariaAkulova](https://t.me/MariaAkulova)  
 🔗 **LinkedIn:**  [maria-akulova](https://www.linkedin.com/in/maria-akulova-96b12220/)  
 **Discord:** Mariia Akulova (@megaandros)

********

### 🎯 Briefly About Me:
I finished RS School as FE-Developer (React) in November 2024 and started volunteering at a sports club in Belgium in February 2025 as WordPress developer and IT support.

I’m a self-motivated learner with a strong passion in IT. Now I'm learning AI Expertise with LLMs.

********

### 🛠 Skills and Proficiency:
```diff
+ Frontend:  HTML5 | CSS3 | JavaScript (ES6+) | React  
+ Tools:     Git | GitHub | VS Code | Antigravity | Netlyfy 
+ QA/Other:  SQL | Jira | Confluence | WordPress (Security, Elementor)  
+ DevOps:    OVH Cloud administration  
+ Soft:      Team leadership | Cross-functional communication  
+ AI:        LLMs (GPT,  Claude(Projects), Gemini(gem), Perplexity, DeepSeek, NotebookLM, Antigravity.)
+ Chatbots: Zappier, Make.com, Manychat, Voiceflow, Chipp.ai, 
```

********


### 💻 Code Showcase:
```javascript
    /* --------------------------------------------
     *   API helpers
     * ------------------------------------------ */
    const fetchCommunes = (postalCode, signal) => {
      const formData = new FormData();
      formData.append("action", "get_communes_by_postal_code");
      formData.append("postal_code", postalCode);
      return fetch(ajaxUrl, {
        method: "POST",
        body: formData,
        credentials: "same-origin",
        signal,
      })
        .then((res) => {
          if (!res.ok) throw new Error(res.status);
          return res.json();
        })
        .then((json) => (json.success ? json.data.map((commune) => commune.name) : []));
    };
```

********

### 📚 Education:

- 🎓 National Metallergical Academy of Ukraine, 1999
- 🎓 University of Maharishy, 2004

********

### 👔 Experience
🧪 IT

- Manual/Automation QA Lead
- QA Manager
- WordPress Developer
- IT Support
- *AI Expert* - in progress 

********

### 🌍 Languages
🇬🇧 English: Upper Intermediate

🇺🇦 Ukrainian: Native

🇷🇺 Russian: Native

🇫🇷 French: A2.2 (Learning!)
