# LPIC-2 Study Guide Project Structure

## Overview

This document outlines the organizational structure of the LPIC-2 Certification Study Guide, designed to provide a systematic approach to learning advanced Linux system administration concepts.

## Directory Architecture

```
lpic2book/
├── README.md                    # Project introduction and overview
├── SUMMARY.md                   # Navigation table of contents
├── LICENCE                      # Creative Commons license
├── PROJECT_STRUCTURE.md         # This documentation file
├── assets/                      # Shared images and media resources
├── exam-201/                    # LPIC-2 Exam 201 materials
│   ├── README.md               # Exam overview and study guidance
│   ├── topic-200/              # Capacity Planning
│   ├── topic-201/              # Linux Kernel
│   ├── topic-202/              # System Startup
│   ├── topic-203/              # Filesystem and Devices
│   ├── topic-204/              # Advanced Storage Device Administration
│   ├── topic-205/              # Network Configuration
│   └── topic-206/              # System Maintenance
└── exam-202/                    # LPIC-2 Exam 202 materials
    ├── README.md               # Exam overview and study guidance
    ├── topic-207/              # Domain Name Server
    ├── topic-208/              # HTTP Services
    ├── topic-209/              # File Sharing
    ├── topic-210/              # Network Client Management
    ├── topic-211/              # E-Mail Services
    └── topic-212/              # System Security
```

## Organizational Principles

### Hierarchical Structure
- **Level 1**: Exam-based separation (201/202)
- **Level 2**: Topic-based organization within each exam
- **Level 3**: Individual study materials and resources

### Naming Conventions
- **Directories**: Lowercase with hyphens (`topic-xxx`)
- **Files**: Preserved original naming for reference integrity
- **Topics**: Numbered according to LPI official objectives

### Content Organization
- **README files**: Provide context and guidance at each level
- **Study materials**: Grouped by official LPI topic numbers
- **Assets**: Centralized media resources for all topics

## Navigation Strategy

### Primary Navigation
1. Start with main `README.md` for project overview
2. Use `SUMMARY.md` for structured navigation
3. Select exam directory based on study focus
4. Browse topics within chosen exam

### Study Path Recommendations
1. **Sequential Learning**: Follow topic order (200→201→202...)
2. **Targeted Study**: Focus on specific weak areas
3. **Review Mode**: Use topic READMEs for quick reference

## File Management

### Content Preservation
- Original file names maintained for reference
- Both numbered and descriptive naming supported
- Historical content preserved during reorganization

### Asset Management
- Centralized `assets/` directory for all media
- Shared resources accessible across all topics
- Consistent image referencing throughout content

## Platform Compatibility

### GitBook Integration
- `SUMMARY.md` provides navigation structure
- Hierarchical organization supports nested menus
- README files create contextual landing pages

### Documentation Platforms
- Markdown format ensures broad compatibility
- Standard directory structure supports various platforms
- Relative linking maintains portability

## Maintenance Guidelines

### Adding Content
1. Place new materials in appropriate topic directory
2. Update relevant README files
3. Add navigation entries to `SUMMARY.md`
4. Ensure asset references are correct

### Updating Structure
1. Maintain backward compatibility
2. Update documentation when making changes
3. Test navigation after structural modifications
4. Preserve existing file references

## Benefits

### For Students
- **Clear Learning Path**: Logical progression through topics
- **Easy Navigation**: Intuitive directory structure
- **Focused Study**: Topic-based organization enables targeted learning

### For Maintainers
- **Scalable Structure**: Easy to add new content
- **Organized Maintenance**: Clear separation of concerns
- **Version Control**: Git-friendly structure for collaboration

### For Platforms
- **Standard Compliance**: Follows documentation best practices
- **Platform Agnostic**: Works with various documentation systems
- **SEO Friendly**: Hierarchical structure supports search optimization

## Future Considerations

- **Expansion**: Structure supports additional exams or certifications
- **Localization**: Directory structure accommodates multiple languages
- **Integration**: Compatible with learning management systems
- **Analytics**: Structure supports usage tracking and optimization
