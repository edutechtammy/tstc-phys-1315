# PHYS-1315 Enhanced Lesson Style Guide
## Comprehensive Guidelines for AI-Assisted Lesson Development

### Course Information
**Course:** PHYS-1315 Physical Science I  
**Institution:** Texas State Technical College (TSTC)  
**Format:** Online Lecture Courses  
**Target Platform:** Canvas LMS  

---

## 1. LESSON ENHANCEMENT PHILOSOPHY

### Core Principles
- **Student-Centered Design**: All content speaks directly to students, using "you" language and personal engagement
- **Career Relevance**: Connect physics concepts to technical career applications (manufacturing, diagnostics, industrial control)
- **Interactive Learning**: Every lesson includes hands-on CidiLabs activities that reinforce key concepts
- **Professional Theme**: Use dp-wrapper structure with proper sectioning and visual hierarchy
- **Real-World Skills**: Emphasize transferable technical skills that apply to TSTC career programs

### Tone and Voice Guidelines
- **Direct Address**: Always use "you" when speaking to students
- **Encouraging and Supportive**: Frame challenges as opportunities for growth
- **Academic but Approachable**: Maintain scientific accuracy while being conversational
- **Real-World Connections**: Link physics concepts to everyday experiences students can relate to

**Example of Correct Tone:**
> "As you explore planetary motion, you'll discover how the same gravitational forces that keep your feet on the ground also orchestrate the cosmic dance of planets around the Sun."

**Avoid Academic Distance:**
> ❌ "Students will learn about gravitational forces and planetary motion."
> ✅ "You'll explore how gravity shapes the movement of planets in our solar system."

---

## 2. TECHNICAL SPECIFICATIONS

### Canvas LMS Requirements
- **No External Files**: All CSS and JavaScript must be inline
- **dp-wrapper Structure**: All content must be wrapped in the specified dp-wrapper div
- **Emoji Icons**: Use emojis instead of Font Awesome or other icon libraries
- **Responsive Design**: Ensure content works on mobile and desktop
- **File Naming**: Canvas versions saved as `index_canvas.html`

### Required HTML Structure
```html
<div id="dp-wrapper" class="dp-wrapper dp-flat-sections variation-1">
    <header class="dp-header dp-flat-sections">
        <div class="dp-content-block kl_custom_block_1">
            <p style="text-align: center;">Module X: [Module Title]</p>
            <p class="dp-progress-placeholder dp-module-progress-completion" style="display: none;">Module Item Completion</p>
        </div>
        <h2 class="dp-heading">
            <span class="dp-header-pre"><span class="dp-header-pre-1">PHYS-1315</span></span> 
            <span class="dp-header-title">[Lesson Title]</span>
        </h2>
    </header>
    <!-- Content sections with proper dp-content-block structure -->
</div>
```

### Color Palette
- **Primary Blue**: #2c3e50 (headers, borders)
- **Accent Blue**: #3498db (section highlights)
- **Success Green**: #27ae60 (interactive activities)
- **Warning Orange**: #f39c12 (important notes)
- **Background**: Linear gradients using these colors
- **Text**: #333 for body text, white for overlay text

---

## 3. LESSON STRUCTURE TEMPLATE

### Required Sections (in order):
1. **dp-header Section** with course title and module navigation
2. **Inspirational Quote** (science-related, using dp-lead styling)
3. **Introduction with Career Connection** (two-column layout with image)
4. **Real-World Skill Connection** (dp-callout highlighting career applications)
5. **Course Competencies and Learning Objectives** (dp-accordion format)
6. **Required Readings** (textbook + enrichment resources in dp-callouts)
7. **Media Section** (videos with dp-panel tabbed interface)
8. **Interactive Activities** (CidiLabs dp-order, dp-si-sort, embedded tools)
9. **Practice and Apply** (conceptual activities and calculations)
10. **Summary/Next Steps** (optional closing section)

### Header Example:
```html
<header class="dp-header dp-flat-sections">
    <div class="dp-content-block kl_custom_block_1">
        <p style="text-align: center;">Module 2: The Universe</p>
        <p class="dp-progress-placeholder dp-module-progress-completion" style="display: none;">Module Item Completion</p>
    </div>
    <h2 class="dp-heading">
        <span class="dp-header-pre"><span class="dp-header-pre-1">PHYS-1315</span></span> 
        <span class="dp-header-title">M2L1 Stars</span>
    </h2>
</header>
```

---

## 4. CIDILABS INTERACTIVE ACTIVITIES

### Activity Selection Criteria
- **Alignment**: Must directly support lesson learning objectives
- **Engagement**: Interactive elements that require student participation
- **Variety**: Use different activity types (sorting, sequencing, matching, classification)
- **Feedback**: Provide immediate feedback and explanations

### Approved Activity Types:
1. **Drag & Drop Sorting** - Categorizing concepts, phenomena, or examples
2. **Sequence Activities** - Ordering processes, timelines, or steps
3. **Classification Games** - Grouping related items or identifying characteristics
4. **Interactive Flip Cards** - Revealing information or definitions
5. **Virtual Labs** - Simulations of scientific processes
6. **Scenario-Based Questions** - Real-world problem solving

### Activity Template:
```html
<div style="background: linear-gradient(135deg, #e8f5e8, #d5eddb); border: 3px solid #27ae60; border-radius: 20px; padding: 30px; margin: 40px 0; box-shadow: 0 6px 20px rgba(39, 174, 96, 0.2);">
    <h3 style="color: #27ae60; margin-bottom: 20px; font-size: 1.5em;">🧪 Interactive Activity: [Title]</h3>
    <div style="background: rgba(255, 255, 255, 0.9); border-radius: 12px; padding: 20px; margin: 20px 0;">
        <p><strong>Instructions:</strong> [Clear, specific instructions for the activity]</p>
    </div>
    [Activity content with drag/drop or interactive elements]
    <div style="background: #e7f3ff; border: 1px solid #b3d7ff; color: #004085; padding: 15px; border-radius: 8px; margin-top: 20px;">
        <p><strong>Feedback:</strong> [Explanation of concepts and learning outcomes]</p>
    </div>
</div>
```

---

## 5. CONTENT DEVELOPMENT GUIDELINES

### Learning Objectives
- **Format**: Use course competency codes (CC#.#) and learning outcome codes (LO#.#.#)
- **Language**: Start with action verbs (Explain, Analyze, Describe, Calculate)
- **Alignment**: Each objective must be assessable through activities or practice questions

### Content Sections
- **Chunking**: Break complex topics into digestible 200-300 word sections
- **Visual Breaks**: Use styled boxes, gradients, and emojis to break up text
- **Examples**: Include real-world applications and relatable analogies
- **Progressive Disclosure**: Start with basics, build to more complex concepts

### Multimedia Integration
- **YouTube Videos**: Embed relevant educational videos (3-6 minutes ideal)
- **NASA Resources**: Link to appropriate NASA educational content
- **NOAA Content**: Use weather/climate resources for relevant topics
- **Image Alt Text**: Provide descriptive alt text for all images

---

## 6. STYLING SPECIFICATIONS

### Typography
- **Primary Font**: Georgia, serif (readable, academic feel)
- **Headings**: 
  - H1: 2.5em, bold, with text-shadow
  - H2: 1.8em, with colored bottom border
  - H3: 1.5em, in activity accent colors
  - H4: 1.3em, for subsections

### Layout Patterns
- **Grid Layouts**: Use CSS Grid for learning objectives and key concepts
- **Responsive Design**: `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))`
- **Spacing**: Consistent 20px padding, 40px margins for sections
- **Border Radius**: 15px for major sections, 10px for subsections

### Box Styling Examples:
```html
<!-- Learning Objectives Box -->
<div style="background: linear-gradient(135deg, #e8f4fd, #d6eaf8); border: 2px solid #3498db; border-radius: 10px; padding: 20px; margin: 20px 0; box-shadow: 0 2px 8px rgba(52, 152, 219, 0.2);">

<!-- Important Note Box -->
<div style="background: linear-gradient(135deg, #fff5cd, #fff2a6); border: 2px solid #f39c12; border-radius: 15px; padding: 25px; margin: 30px 0; box-shadow: 0 4px 15px rgba(243, 156, 18, 0.2);">

<!-- Activity Box -->
<div style="background: linear-gradient(135deg, #e8f5e8, #d5eddb); border: 3px solid #27ae60; border-radius: 20px; padding: 30px; margin: 40px 0; box-shadow: 0 6px 20px rgba(39, 174, 96, 0.2);">
```

---

## 7. COMMON MISTAKES TO AVOID

### Technical Issues
- ❌ **External Dependencies**: Never link to external CSS or JavaScript files
- ❌ **Font Awesome Icons**: Use emojis instead (🔬 ⚗️ 🌟 📊 🧪 🔍)
- ❌ **Complex JavaScript**: Canvas LMS has limited JavaScript support
- ❌ **Absolute Positioning**: Can break in Canvas responsive layout

### Content Issues
- ❌ **Third Person Language**: "Students will learn" → "You will discover"
- ❌ **Passive Voice**: "Concepts are explained" → "You'll explore concepts"
- ❌ **Academic Jargon**: Define terms clearly and use accessible language
- ❌ **Wall of Text**: Break up long paragraphs with visual elements

### Design Issues
- ❌ **Inconsistent Spacing**: Use systematic padding/margin values
- ❌ **Poor Color Contrast**: Ensure text is readable on background colors
- ❌ **Missing Responsive Design**: Test on mobile and tablet sizes
- ❌ **Overuse of Effects**: Too many gradients/shadows can be distracting

---

## 8. QUALITY ASSURANCE CHECKLIST

### Before Submitting Enhanced Lessons:
- [ ] All content addresses students directly with "you" language
- [ ] 2-3 interactive CidiLabs activities included and properly styled
- [ ] Learning objectives clearly stated and tied to course competencies
- [ ] All external dependencies removed for Canvas compatibility
- [ ] Emojis used instead of icon fonts
- [ ] dp-wrapper structure properly implemented
- [ ] Responsive design tested
- [ ] All links work and open in new tabs
- [ ] Practice questions include expandable answers
- [ ] Footer includes course info and next lesson preview

### Content Validation:
- [ ] Scientific accuracy verified
- [ ] Real-world connections made
- [ ] Appropriate reading level (undergraduate introductory)
- [ ] Inclusive and accessible language used
- [ ] Video content enhances rather than replaces text

---

## 9. EXAMPLE LESSON REFERENCE

### Primary Reference Model:
**M2L1 Stars** - This represents the gold standard for enhanced lesson development with the following exemplary features:

#### Professional Theme Implementation:
- **dp-wrapper Structure**: Properly implemented with `class="dp-wrapper dp-flat-sections variation-1"`
- **Sectioned Design**: Clear visual hierarchy with `dp-content-block` sections and `dp-hr-plain` dividers
- **Professional Layout**: Uses column containers and responsive grid system (`dp-col-2-eq`)

#### Engaging Introduction:
```html
<p class="dp-lead" style="text-align: center;">
<span style="font-size: 24pt;"><em>"The cosmos is within us. We are made of star-stuff.<br />We are a way for the universe to know itself."</em></span><br />
<span>&mdash;&nbsp;Carl Sagan</span>
</p>
```

#### Career Connection Excellence:
- **Real-World Skills**: "These skills—processing large data sets, understanding sensor calibration, and computational analysis—are directly transferable to careers in industrial control, advanced manufacturing, and technical diagnostics."
- **Technical Applications**: Links astronomical techniques to HVAC/electrical diagnostics, aviation testing, manufacturing quality control

#### Interactive Activity Integration:
- **CidiLabs dp-order Activities**: Star lifecycle sequencing with visual figures
- **External Interactive Tools**: Embedded star color/temperature and HR diagram tools
- **dp-si-sort-pool Activities**: Drag-and-drop stage matching with professional styling

#### Student-Centered Language:
- **Direct Engagement**: "Look up at the night sky. Every single star you see..."
- **Personal Connection**: "You'll discover the star's entire life cycle..."
- **Skill Building**: "By the end of this lesson, you'll gain the skills to perform your own astronomical work..."

### Key Success Factors from M2L1:
1. **Professional Theme Consistency** using dp-wrapper and proper class structure
2. **Career Relevance** connecting physics to technical career applications
3. **Multi-Modal Learning** with videos, interactive tools, and hands-on activities
4. **Visual Design** with figures, callouts, and structured content blocks
5. **Student Engagement** through direct address and inspiring introductions

---

## 10. TROUBLESHOOTING COMMON AI ISSUES

### When AI Reverts to Default Behavior:
- **Remind** about Canvas inline-only styling requirements
- **Reference** this style guide document
- **Provide** specific examples from successful lessons
- **Check** token limits and start fresh conversation if needed

### When Content Becomes Too Academic:
- **Prompt** for more direct student engagement
- **Ask** for real-world examples and analogies
- **Request** conversion of passive to active voice
- **Emphasize** conversational tone while maintaining scientific accuracy

### When Activities Don't Align:
- **Review** learning objectives first
- **Specify** exact activity type needed
- **Provide** examples of successful activities
- **Ensure** feedback explains the educational purpose

---

## 11. HANDOFF PROTOCOL

### When Transferring to New AI:
1. **Provide** this complete style guide
2. **Share** 2-3 successful lesson examples
3. **Highlight** specific requirements for current module
4. **Test** with one lesson before proceeding with batch work
5. **Verify** understanding of Canvas LMS constraints

### Conversation Management:
- **Monitor** token usage and start fresh before hitting limits
- **Reference** style guide when AI behavior changes
- **Provide** specific feedback on deviations
- **Maintain** consistency across all lessons in a module

---

**Last Updated:** January 13, 2026  
**Version:** 1.0  
**Maintainer:** PHYS-1315 Development Team

---

*This style guide represents the accumulated knowledge from successful lesson enhancements and should be referenced for all future AI-assisted lesson development to ensure consistency, quality, and Canvas LMS compatibility.*