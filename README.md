# agents-marketplace

A Claude Code marketplace for hierarchical agent systems, documentation management, and continuous learning plugins.

## Available Plugins

### agents-learning-system

Capture, track, and implement learnings with hierarchical storage and closed-loop tracking across profiles.

**Features**:
- Hierarchical storage (global/profile/project/agent)
- Closed-loop tracking with documentation-first approach
- Cross-profile pattern extraction
- Robust search across all profiles
- 97% closed-loop rate proven in production use

**Commands**:
- `/learn` - Capture a learning
- `/implement-learnings` - Apply captured learnings

**Repository**: https://github.com/pjbeyer/agents-learning-system

### agents-documentation-suite

Hierarchical documentation system with audience specialization (human/machine/team/public) and multi-platform publishing.

**Features**:
- 13 specialized skills (writing, management, optimization, orchestration)
- Single `/doc` command with subcommands
- Audience-specific optimization (human/machine/team/public)
- Multi-platform publishing (Notion, GitHub, local)
- Token-efficient machine documentation

**Commands**:
- `/doc write --audience=<audience>` - Write documentation
- `/doc maintain` - Maintain and update docs
- `/doc optimize` - Optimize for token efficiency
- `/doc publish --platform=<platform>` - Publish to platforms
- `/doc curate` - Curate agent documentation
- `/doc coordinate --level=<level>` - Coordinate hierarchical docs
- `/doc organize` - Organize multi-agent systems

**Repository**: https://github.com/pjbeyer/agents-documentation-suite

### agents-context-system

Manage hierarchical agent infrastructure, AGENTS.md optimization, MCP configuration, and smart context loading.

**Features**:
- 9 specialized skills (optimization, hierarchy, context, tasks)
- Smart context loading (40% token savings)
- Profile-aware standards (pjbeyer/work/play/home)
- Token-efficient AGENTS.md optimization
- MCP configuration management

**Commands**:
- `/optimize-agents` - Optimize AGENTS.md files
- `/optimize-mcp` - Optimize MCP configuration
- `/add-task` - Add hierarchy-aware tasks

**Repository**: https://github.com/pjbeyer/agents-context-system

## Installation

### Add Marketplace

```bash
/plugin marketplace add pjbeyer/agents-marketplace
```

### Install Plugins

```bash
# Install learning system
/plugin install agents-learning-system@agents-marketplace

# Install documentation suite (when available)
/plugin install agents-documentation-suite@agents-marketplace

# Install agent system (when available)
/plugin install agents-agent-system@agents-marketplace
```

## Philosophy

These plugins follow a hierarchical organization principle:

### Hierarchy Levels

1. **Global** (`~/Projects`) - Cross-profile patterns and standards
2. **Profile** (`~/Projects/{profile}`) - Profile-specific tools and workflows
3. **Project** - Project-specific patterns and documentation
4. **Agent** - Agent-specific capabilities and improvements

### Key Principles

1. **Information at the Right Level**: No duplication across hierarchy
2. **Token Efficiency**: Optimized context loading based on level
3. **Closed-Loop Learning**: Documentation-first approach with verification
4. **Cross-Profile Patterns**: Extract and share patterns appropriately
5. **Profile-Aware**: Respects different standards across contexts

## Development

### Plugin Naming Convention

All plugins in this marketplace use the `agents-` prefix:
- `agents-learning-system`
- `agents-documentation-suite`
- `agents-agent-system`

### Contributing

These plugins are open source. Contributions welcome via GitHub pull requests.

### Testing Locally

For plugin development:

```bash
# Add local marketplace
/plugin marketplace add /Users/pjbeyer/Projects/pjbeyer/agents-marketplace

# Install from local marketplace
/plugin install agents-learning-system@agents-marketplace
```

## License

All plugins in this marketplace are released under MIT License.

## Author

Paul Beyer
- Email: paul@pjbeyer.com
- GitHub: https://github.com/pjbeyer

## Version

1.0.0
