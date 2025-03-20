# Alto CERO 2.0 Documentation

This repository contains the technical documentation for the Alto CERO 2.0 platform, a comprehensive Chiller Plant Management System (CPMS) designed to optimize building operations and reduce energy consumption.

## Documentation Structure

The documentation is built using [Mintlify](https://www.mintlify.com/), a modern documentation platform. The structure is organized as follows:

```
📁 Root
├── 📄 index.mdx                 # Home page with system overview
├── 📄 docs.json                 # Navigation configuration
├── 📁 getting-started           # Quick start guides
├── 📁 architecture              # System architecture overview
├── 📁 components                # Detailed component documentation
├── 📁 installation              # Installation guides
├── 📁 configuration             # Configuration reference
├── 📁 operations                # Day-to-day operations
├── 📁 api-reference             # API documentation
├── 📁 monitoring                # Monitoring and observability
├── 📁 troubleshooting           # Troubleshooting guides
├── 📁 developer-guide           # For developers extending the system
└── 📁 images                    # Images and diagrams
```

## Development

To run the documentation locally, you need to have Node.js installed and then install the Mintlify CLI:

```bash
npm i -g mintlify
```

Then, run the following command in the repository root:

```bash
mintlify dev
```

The documentation will be available at [http://localhost:3000](http://localhost:3000).

## Adding Content

### Adding a New Page

1. Create a new Markdown or MDX file in the appropriate directory
2. Add YAML frontmatter at the top of the file:
   ```yaml
   ---
   title: 'Your Page Title'
   description: 'Brief description of the page'
   ---
   ```
3. Add the page to the navigation in `docs.json`

### Adding Images

1. Place images in the `images` directory
2. Reference them in your Markdown using:
   ```markdown
   <Frame>
     <img src="/images/your-image.png" alt="Description" />
   </Frame>
   ```

### Interactive Components

Mintlify provides several interactive components you can use:

- Cards and CardGroups
- Tabs
- Accordions
- Steps
- Callouts (Note, Warning, etc.)
- API Reference components (for the API documentation)

See the [Mintlify components documentation](https://mintlify.com/docs/components/overview) for details.

## Best Practices

- Keep pages focused on a single topic
- Use clear, concise language
- Include examples and code snippets where appropriate
- Use interactive components to improve readability
- Include diagrams and screenshots to visualize concepts
- Link related pages to help users navigate the documentation

## Update Process

1. Make changes to the documentation files
2. Test locally using `mintlify dev`
3. Commit changes to the repository
4. Push changes to the main branch
5. The documentation will be automatically deployed

## Technical Writer Guidelines

- **Consistency**: Maintain consistent terminology throughout the documentation
- **Audience**: Write for both technical and non-technical users
- **Structure**: Use clear headings and subheadings
- **Examples**: Include practical examples and use cases
- **Formatting**: Use formatting (code blocks, bold, italic) to improve readability
- **Update Frequency**: Update documentation whenever the product changes

## Image Guidelines

- Use PNG format for diagrams and screenshots
- Keep image file sizes reasonable (optimize before adding)
- Provide descriptive alt text for accessibility
- Use consistent styling for diagrams
- Use dark/light mode compatible colors when possible

## Contact

For questions about the documentation, please contact:

- Documentation Team: docs@altotech.ai
- Technical Support: support@altotech.ai 