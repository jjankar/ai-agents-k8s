# 🧠 AI Agents K8s - Local Installation with Ansible

This guide walks you through setting up the AI Agents K8s project using Ansible. It installs the [Dify](https://github.com/langgenius/dify) application locally on your machine.

---

## 🚀 Prerequisites

- Ubuntu/Debian-based Linux system
- [Ansible](https://docs.ansible.com/)
- Git
- Internet access for downloading dependencies

---

## 📦 Installation Steps

### 1. Install Ansible

```bash
sudo apt update
sudo apt install ansible
```

---

### 2. Clone the Repository

```bash
git clone https://github.com/jjankar/ai-agents-k8s.git
```

---

### 3. Navigate to the Playbooks Directory

```bash
cd ai-agents-k8s/dify
```

---

### 4. Run the Ansible Playbook

This will install and configure Dify locally:

```bash
ansible-playbook -i inventory_local.ini install_dify_local.yml
```

---

### 5. Open Dify in Your Browser

Once the playbook completes, visit:

[http://localhost](http://localhost)

---

## 🛠️ Troubleshooting

If you encounter issues:
- Ensure all dependencies are installed.
- Check Ansible output for errors.
- Try restarting your machine or network services.

---