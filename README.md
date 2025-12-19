# Collapse Rules & Ten Commandments

A philosophical and computational exploration of the relationship between physical laws (collapse rules) and moral principles (Ten Commandments), presented as an interactive web application.

## Overview

This project demonstrates how physical collapse rules that govern causality and reality mirror the moral principles found in the Ten Commandments. It includes:

- **Visual representation** of the Ten Commandments as two stone tablets
- **Interactive comparison** between 10 collapse rules and the Ten Commandments
- **Fork bomb testing** to see how rules and commandments prevent destructive processes
- **Cancer examples** showing how collapse rules apply to biological systems

## Features

### 🗿 Two Stone Tablets
- Beautifully rendered stone tablets displaying the Ten Commandments
- First tablet: Commandments 1-5 (Duties to God)
- Second tablet: Commandments 6-10 (Duties to Others)
- 3D perspective with stone texture and realistic shadows

### 📊 Comparison View
Maps each of the 10 collapse rules to corresponding commandments:

1. **Unlimited copies violate causality** → Thou shalt not make graven images (2)
2. **Entities without origin invalidated** → Honor your father and mother (5)
3. **Effects may not recursively cause** → Thou shalt not take the name in vain (3)
4. **Branching timelines collapsed** → Thou shalt have no other gods (1)
5. **Unobservable states rejected** → Thou shalt not bear false witness (9)
6. **Processes destroying host deleted** → Thou shalt not murder (6)
7. **Order without cost forbidden** → Remember the Sabbath (4)
8. **Inconsistent histories cannot persist** → Thou shalt not bear false witness (9)
9. **Timelines that never progress pruned** → Remember the Sabbath (4)
10. **Unauthorized timeline edits reversed** → Thou shalt not steal (8)

### 💣 Fork Bomb Testing
Interactive simulator that tests fork bombs against:
- All 10 collapse rules
- All 10 commandments
- Shows which rules prevent fork bombs and why
- Adjustable parameters (replication rate, process count, generations)

### 🧬 Cancer Examples
Demonstrates how collapse rules apply to different cancer types:
- Rapidly dividing solid tumors
- Cancer stem cell–driven tumors
- Hormone-driven cancers
- Metastatic cancers
- And 6 more examples

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required - it's a static HTML file!

### Installation

1. Clone or download this repository:
```bash
git clone <repository-url>
cd cancer
```

2. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or simply double-click the `index.html` file.

## Usage

### Navigating the Application

The application has four main tabs:

1. **Ten Commandments** - View the commandments on stone tablets
2. **Comparison** - See how collapse rules map to commandments
3. **Fork Bomb Testing** - Test fork bombs interactively
4. **Cancer Examples** - Explore cancer type examples

### Testing Fork Bombs

1. Navigate to the "Fork Bomb Testing" tab
2. Adjust the parameters:
   - **Replication Rate**: How many processes each fork creates (default: 2)
   - **Initial Process Count**: Starting number of processes (default: 1)
   - **Fork Generations**: Number of fork iterations (default: 3)
3. Click "Test Fork Bomb"
4. View results showing which rules and commandments prevent the fork bomb

## Project Structure

```
cancer/
├── index.html          # Main application file (HTML, CSS, JavaScript)
└── README.md          # This file
```

## Technical Details

### Collapse Rules

The collapse rules are functions that enforce physical constraints:

- **unlimited_copies_violate_causality**: Limits replication rate to 1
- **entities_without_origin_invalidated**: Invalidates entities without origin
- **effects_may_not_recursively_cause**: Prevents recursive self-causation
- **branching_timelines_collapsed**: Collapses multiple branches to one
- **unobservable_states_rejected**: Rejects unobservable states
- **processes_destroying_host_deleted**: Deletes processes that destroy host
- **order_without_cost_forbidden**: Prevents negative entropy
- **inconsistent_histories_cannot_persist**: Erases inconsistent histories
- **timelines_that_never_progress_pruned**: Prunes non-progressing timelines
- **unauthorized_timeline_edits_reversed**: Reverses unauthorized edits

### Ten Commandments

The Ten Commandments are implemented as functions that enforce moral constraints, mirroring the structure of collapse rules.

## Philosophy

This project explores the idea that:
- Physical laws and moral principles share underlying structures
- Constraints on reality (collapse rules) parallel constraints on behavior (commandments)
- Both systems prevent destructive, unsustainable, or impossible states
- The same patterns appear in physics, ethics, and computation

## Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (responsive design)

## Contributing

This is a philosophical/educational project. Feel free to:
- Suggest improvements to the visual design
- Add more examples or test cases
- Enhance the comparison mappings
- Improve documentation

## License

This project is provided as-is for educational and philosophical exploration purposes.

## Acknowledgments

- Inspired by the relationship between physical laws and moral principles
- Ten Commandments text based on traditional biblical translations
- Stone tablet design inspired by classical representations

## Future Enhancements

### Visual & UI Improvements
- [ ] More interactive visualizations with animated transitions
- [ ] 3D rotating stone tablets with mouse/touch interaction
- [ ] Particle effects and visual feedback when rules are applied
- [ ] Dark mode / light mode toggle
- [ ] Customizable color themes
- [ ] Animated transitions between states and tabs
- [ ] Progress indicators for fork bomb simulation
- [ ] Interactive timeline visualization for fork bomb growth
- [ ] Visual comparison charts (bar charts, graphs)
- [ ] Hover tooltips with detailed explanations
- [ ] Smooth scroll animations
- [ ] Tablet break/crack animations when rules are violated

### Interactive Features
- [ ] Clickable commandments that show corresponding collapse rules
- [ ] Interactive rule builder to create custom collapse rules
- [ ] Real-time parameter adjustment with live preview
- [ ] Drag-and-drop interface for reordering comparisons
- [ ] Interactive entity editor for creating custom test cases
- [ ] Side-by-side before/after comparison views
- [ ] Expandable/collapsible sections for detailed information
- [ ] Interactive tutorial/walkthrough for first-time users
- [ ] Command palette for quick navigation
- [ ] Keyboard shortcuts for power users

### Test Cases & Examples
- [ ] Additional test cases beyond fork bombs (viruses, malware, etc.)
- [ ] Biological system examples (beyond cancer)
- [ ] Physical system examples (black holes, quantum states)
- [ ] Social system examples (economies, societies)
- [ ] Custom test case creator
- [ ] Test case library with saved examples
- [ ] Batch testing multiple scenarios
- [ ] Historical examples showing rule violations
- [ ] Edge case testing (boundary conditions)
- [ ] Stress testing with extreme parameters

### Data & Export Features
- [ ] Export functionality for test results (JSON, CSV, PDF)
- [ ] Save/load test configurations
- [ ] Shareable links for specific test scenarios
- [ ] Print-friendly version of tablets and comparisons
- [ ] Screenshot/capture functionality
- [ ] Data visualization exports (charts, graphs)
- [ ] Report generation with detailed analysis
- [ ] Export comparison tables to spreadsheets
- [ ] Bookmark specific views or test results
- [ ] History of previous tests

### Educational Features
- [ ] More detailed explanations of each rule/commandment pairing
- [ ] Interactive glossary of terms
- [ ] Philosophical essays on each pairing
- [ ] Video tutorials explaining concepts
- [ ] Quiz mode to test understanding
- [ ] Case study deep-dives
- [ ] References and citations section
- [ ] "Learn More" links to external resources
- [ ] Step-by-step walkthroughs
- [ ] Concept maps showing relationships
- [ ] FAQ section addressing common questions
- [ ] Historical context for each commandment

### Technical Improvements
- [ ] Performance optimizations for large simulations
- [ ] Web Workers for heavy computations
- [ ] Service Worker for offline functionality
- [ ] Progressive Web App (PWA) support
- [ ] Local storage for user preferences
- [ ] IndexedDB for large data storage
- [ ] Modular code architecture (ES6 modules)
- [ ] Unit tests and integration tests
- [ ] Code documentation (JSDoc)
- [ ] Build system (Webpack, Vite, etc.)
- [ ] TypeScript migration for type safety
- [ ] Accessibility improvements (ARIA labels, screen reader support)
- [ ] Internationalization (i18n) support for multiple languages
- [ ] SEO optimization

### Analysis & Insights
- [ ] Statistical analysis of rule effectiveness
- [ ] Pattern recognition in test results
- [ ] Comparative analysis between different test cases
- [ ] Trend analysis over multiple tests
- [ ] Correlation analysis between rules
- [ ] Effectiveness scoring system
- [ ] Predictive modeling for rule outcomes
- [ ] Machine learning integration for pattern detection
- [ ] Heat maps showing rule violation frequency
- [ ] Network graphs showing rule relationships

### Content Additions
- [ ] Additional collapse rules beyond the original 10
- [ ] Other religious/moral code comparisons
- [ ] Scientific law comparisons (thermodynamics, quantum mechanics)
- [ ] Historical evolution of rules and commandments
- [ ] Cultural variations of moral codes
- [ ] Modern interpretations and applications
- [ ] Real-world case studies
- [ ] Expert commentary and analysis
- [ ] User-submitted examples and stories
- [ ] Community discussions/forums

### Integration Features
- [ ] API for programmatic access
- [ ] REST API for backend integration
- [ ] WebSocket support for real-time collaboration
- [ ] Social media sharing buttons
- [ ] Embeddable widgets for other websites
- [ ] Browser extension version
- [ ] Mobile app version (React Native, Flutter)
- [ ] Desktop app version (Electron)
- [ ] Integration with educational platforms (LMS)
- [ ] GitHub integration for version control

### Accessibility & Usability
- [ ] Full keyboard navigation
- [ ] Screen reader optimization
- [ ] High contrast mode
- [ ] Font size adjustment
- [ ] Reduced motion options
- [ ] Colorblind-friendly color schemes
- [ ] Multi-language support
- [ ] Right-to-left (RTL) language support
- [ ] Voice commands
- [ ] Text-to-speech for commandments

### Advanced Features
- [ ] Rule composition (combining multiple rules)
- [ ] Rule conflict detection and resolution
- [ ] Temporal analysis (how rules change over time)
- [ ] Multi-dimensional rule space visualization
- [ ] Rule effectiveness metrics
- [ ] Custom rule validation
- [ ] Rule versioning system
- [ ] Collaborative rule editing
- [ ] Rule marketplace/sharing platform
- [ ] AI-powered rule suggestions
- [ ] Simulation replay functionality
- [ ] Time-travel debugging for simulations

---

**Note**: This is an educational and philosophical exploration. The comparisons between physical laws and moral principles are metaphorical and intended for contemplation and discussion.

