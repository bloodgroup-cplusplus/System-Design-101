# System Design 101

A comprehensive collection of system design courses and learning materials for the Algoroq learning platform. This repository contains structured courses covering fundamental to advanced system design concepts, patterns, and best practices.

## About

System Design 101 provides high-quality educational content focused on:

- Core system design principles and patterns
- Scalability and performance optimization
- Distributed systems architecture
- Database design and selection
- Caching strategies and implementations
- Load balancing and fault tolerance
- Microservices and API design
- Real-world case studies and applications

## Repository Structure

Courses are organized at the root level with a consistent structure:

```
System-Design-101/
├── introduction-to-ai/              # Course directory
│   ├── course.json                  # Course metadata
│   ├── getting-started/             # Section directory
│   │   ├── section.json             # Section metadata
│   │   ├── 01-what-is-ai.md         # Topic content
│   │   └── 02-types-of-ai.md
│   └── machine-learning-basics/
│       ├── section.json
│       └── 01-intro-to-ml.md
└── CONTRIBUTING.md                  # Contribution guidelines
```

### For Contributors

We welcome contributions to improve and expand the course content. Please see [CONTRIBUTING.md](CONTRIBUTING.md) for:

- Repository structure guidelines
- File format specifications
- Content quality standards
- Contribution workflow
- Testing procedures

## Content Format

All course content uses a structured format:

**Course Metadata** (`course.json`)

```json
{
  "slug": "course-identifier",
  "title": "Course Title",
  "description": "Course description",
  "difficulty": "Beginner|Intermediate|Advanced",
  "duration": "X weeks",
  "category": "Category name",
  "featured": true|false,
  "premium": true|false,
  "available": true|false
}
```

**Topic Content** (`.md` files with YAML frontmatter)

```markdown
---
slug: topic-identifier
title: Topic Title
readTime: 10 min
orderIndex: 1
premium: false
---

# Topic Content

Markdown content here...
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for complete format specifications.

## Sync and Updates

Content from this repository syncs to the Algorok platform through a manual sync process:

- Platform administrators trigger syncs from the admin interface
- Content is matched by slugs to preserve user progress
- New content is created, existing content is updated
- Changes appear on the platform after successful sync

## License

All content in this repository is provided for educational purposes. Please respect intellectual property and attribution requirements when contributing.

## Questions and Support

For questions about:

- **Content contributions**: See [CONTRIBUTING.md](CONTRIBUTING.md)
- **Platform access**: Visit the Algorok learning platform
- **Technical issues**: Open an issue in this repository

---

Built for the Algorok learning platform - Making system design education accessible and structured.
