# RepoSetup
Quick Setup Guide for INDICATE Repositories This package contains everything you need to set up GitHub contribution processes for your INDICATE repository.

---

The Repository scope is to:
1. Communication of supporting work, such as minimal viable data set, use case development. 
2. Allow INDICATE participants to collaborate and publish code to co-develop indicate. 
3. It is NOT intended to support IaC for INDICATE central services. 
4. It is NOT intended to for federated analysis or federated learning projects.

In other words it is for
✅ Developing definitions of the Common Data Model  
✅ Use case development  
✅ INDICATE platform co-development  
❌ NOT for IaC central services  
❌ NOT for study packages/research code  

---

## 📦 What's Included

- **GETTING_STARTED.md** - 15-minute setup guide (start here!)
- **CONTRIBUTING.md** - Developer contribution guide
- **CODEOWNERS** - Code review assignments
- **pull_request_template.md** - Pull request template
- **LICENSE** - EUPL-1.2 license text

---

## 🚀 Quick Start

### Step 1: Read the Setup Guide

Open **[GETTING_STARTED.md](./GETTING_STARTED.md)** and follow the instructions.

**Total setup time: ~15 minutes**

### Step 2: Copy Files

Copy these files to your repository:

```bash
# In your repository root
cp CONTRIBUTING.md ./CONTRIBUTING.md
cp LICENSE ./LICENSE

# Create .github directory if it doesn't exist
mkdir -p .github/workflows

# Copy GitHub-specific files
cp CODEOWNERS ./.github/CODEOWNERS
cp pull_request_template.md ./.github/pull_request_template.md
```

### Step 3: Create Teams & Enable Protection

See [GETTING_STARTED.md](./GETTING_STARTED.md) for:
- Creating GitHub teams
- Enabling branch protection
- Testing your setup

---

## ✨ What You Get

- ✅ Code review process (automatic reviewer assignment)
- ✅ Pull request templates
- ✅ EUPL-1.2 licensing compliance

---

## 📞 Support

**General Questions and Support**: info@indicate-europe.eu

---

## 📝 License

**European Union Public License (EUPL) v1.2**

Copyright © 2025 INDICATE Consortium

---

**Ready to start? Open [GETTING_STARTED.md](./GETTING_STARTED.md) now!**
