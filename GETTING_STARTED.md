# Getting Started with INDICATE GitHub

## Quick Setup (15 minutes)

### Step 1: Add Files to Your Repository

Copy these files to your repository:

```
your-repository/
├── .github/
│   ├── workflows/
│   ├── CODEOWNERS                    # Copy from CODEOWNERS
│   └── pull_request_template.md      # Copy from Pull_request_template.md
├── CONTRIBUTING.md                   # Copy from Contributing.md
├── LICENSE                           # Download EUPL-1.2 (see below)
└── README.md                         # Your repository README
```

### Step 2: Get the License File

Download the EUPL-1.2 license:

```bash
# Download license file
curl -o LICENSE https://joinup.ec.europa.eu/sites/default/files/custom-page/attachment/2020-03/EUPL-1.2%20EN.txt
```

Or create a `LICENSE` file with:
```
European Union Public Licence (EUPL) v. 1.2

Copyright (c) 2025 INDICATE Consortium

[Full text at: https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12]
```

## That's It!

Your repository is now set up with:
- ✅ Automated quality checks
- ✅ Code review assignments
- ✅ Pull request templates
- ✅ Contribution guidelines
- ✅ Branch protection

## Customization (Optional)

### Adjust CODEOWNERS

Edit `.github/CODEOWNERS` to match your team structure:

```
# Example: Make Jane and John review Python code
*.py    @jane @john
```

### Update Contributing Guide

Edit `CONTRIBUTING.md`:
- Add repository-specific setup instructions
- Update contact information
- Add examples relevant to your code

## Common Issues

**Issue: CI fails on first run**
- Check that your code follows the formatting rules
- Run checks locally first: `black src/`, `flake8 src/`

**Issue: No reviewers assigned**
- Verify GitHub teams exist
- Check team members are correct
- Review CODEOWNERS file paths

**Issue: Can't push to main**
- Good! Branch protection is working
- Create a branch and PR instead

## Next Steps

1. Read the [Contributing Guide](./CONTRIBUTING.md)
2. Review existing code standards
3. Make your first contribution!
