# Commercial Restricted License (CRL)

A dual-licensing model that enables open source development while protecting commercial interests.

## Overview

The **Commercial Restricted License (CRL)** is a software license designed to bridge the gap between fully open and fully proprietary software. It allows unrestricted non-commercial use while requiring explicit permission and licensing for commercial applications.

## Key Features

- ✅ **Free for non-commercial use** - Personal projects, academic research, and open source
- 💼 **Commercial licensing available** - Revenue-generating use requires separate license
- 🔒 **Clear boundaries** - Explicit definitions of commercial vs non-commercial use
- 📜 **Standard format** - Easy to understand and implement
- ⚖️ **Legal clarity** - Reduces ambiguity around usage rights

## How It Works

### Non-Commercial Use (Free)

The following uses are **permitted without additional licensing**:

- Personal use, learning, and experimentation
- Academic research and education
- Open source projects that are not monetized
- Internal evaluation within commercial organizations (limited to 30 days)
- Use by registered non-profit organizations

### Commercial Use (License Required)

The following uses **require a commercial license**:

- Use in revenue-generating products or services
- Integration into commercial software
- Use by for-profit organizations in business operations
- Paid consulting, support, or services using the software
- Organizations with annual revenue exceeding $100,000 USD

## Quick Start

### For Software Authors

1. Copy the `CRL.md` file to your project
2. Replace the placeholders:
   - `[YEAR]` with the copyright year
   - `[YOUR NAME]` with your name or organization
   - `[YOUR COUNTRY]` with your jurisdiction
3. Add this to your project's main README:

```markdown
## License

This project is licensed under the Commercial Restricted License (CRL) v1.1.
See [LICENSE.md](LICENSE.md) for details.

For commercial use, please contact [your-email@example.com] for licensing options.
```

### For Users

1. **Non-commercial use**: You can use the software freely under the terms in `CRL.md`
2. **Commercial use**: Contact the copyright holder to discuss commercial licensing
3. **Unsure?** Review the definitions in the license or contact the author

## License Text

The complete license text is available in [`CRL.md`](CRL.md).

## Why CRL?

### Problems with Existing Licenses

- **MIT/Apache**: Too permissive, allows unrestricted commercial use
- **GPL**: Too restrictive, requires derivative works to be open source
- **Dual licensing**: Often unclear or requires complex legal structures

### CRL Advantages

- **Clear commercial boundaries** with specific revenue thresholds
- **Simple implementation** with standard license format
- **Flexible licensing** for different commercial scenarios
- **Familiar structure** based on established license patterns

## Comparison with Other Licenses

| License | Non-Commercial | Commercial | Copyleft | Complexity |
|---------|----------------|------------|----------|------------|
| MIT | ✅ Free | ✅ Free | ❌ No | Low |
| GPL v3 | ✅ Free | ✅ Free* | ✅ Yes | High |
| CC BY-NC | ✅ Free | ❌ Restricted | ❌ No | Medium |
| **CRL** | ✅ Free | 💼 License Required | ❌ No | Low |

*GPL allows commercial use but requires source disclosure

## Implementation Examples

### In Your README

```markdown
## License

Licensed under the Commercial Restricted License (CRL) v1.1.

- ✅ **Free** for non-commercial use
- 💼 **Commercial license** required for business use

Contact: commercial@yourcompany.com
```

### In Your Source Code

```python
"""
Copyright (c) [YEAR] [YOUR NAME]

Licensed under the Commercial Restricted License (CRL) v1.1.
See LICENSE file for details.

For commercial licensing, contact: license@yourcompany.com
"""
```

## Commercial Licensing

If you're a software author using CRL, consider these commercial licensing models:

### Pricing Models
- **Per-developer** licensing
- **Revenue-based** percentage fees  
- **Enterprise** unlimited licenses
- **SaaS** usage-based pricing

### License Terms
- **Perpetual** vs **subscription** licensing
- **Support and maintenance** inclusions
- **Customization and modifications** rights
- **Redistribution** permissions

## Legal Considerations

### For Authors
- Ensure you own or have rights to license the software
- Consider trademark protection for your project name
- Maintain clear records of license agreements
- Consult legal counsel for complex licensing scenarios

### For Users
- Review the commercial use definitions carefully
- When in doubt, contact the copyright holder
- Document your intended use case
- Consider future growth when evaluating commercial thresholds

## FAQ

**Q: Is CRL OSI-approved?**  
A: No, CRL restricts commercial use and therefore doesn't meet OSI's definition of open source.

**Q: Can I modify CRL-licensed software?**  
A: Yes, for non-commercial use. Commercial use of modifications requires licensing.

**Q: What if my non-profit becomes commercial?**  
A: You would need to obtain commercial licensing at that point.

**Q: How is "commercial use" enforced?**  
A: Copyright holders can pursue legal action for unauthorized commercial use.

**Q: Can I use CRL for my own projects?**  
A: Yes! CRL itself is MIT-licensed, so you can freely use it for your projects.

## Contributing

We welcome contributions to improve the CRL license template:

1. Fork this repository
2. Create a feature branch
3. Submit a pull request with your improvements

## Support

- 📧 **General questions**: Open an issue in this repository
- 💼 **Commercial licensing**: Contact the specific software author
- 📚 **Legal advice**: Consult qualified legal counsel

## Changelog

### Version 1.1 (2025)
- Updated placeholder format from angle brackets (`<>`) to square brackets (`[]`)
- Improved text formatting in "No Warranty" section for better readability
- Updated liability clause to reference "AUTHORS OR COPYRIGHT HOLDERS"
- Enhanced consistency in legal terminology
- Removed the need to clearly mark any modifications made to the Software

### Version 1.0 (2025)
- Initial release of Commercial Restricted License
- Clear commercial/non-commercial definitions
- Standard license format
- Revenue threshold guidelines

---

**Note**: This license template is provided for informational purposes. Always consult legal counsel for specific licensing needs.

## License

This CRL license template and documentation is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for details.
