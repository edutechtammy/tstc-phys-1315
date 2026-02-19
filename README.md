
# PHYS-1315 Physical Science I: Curriculum Upgrade Project

## Project Overview

This project is a comprehensive upgrade of the PHYS-1315 Physical Science I lecture course, focused on:
- Ensuring every lesson explicitly covers its Learning Objectives (LOs)
- Upgrading all lessons to a modern, interactive HTML theme (with CidiLabs)
- Organizing and enriching resources for each lesson (images, transcripts, interactives, etc.)
- Providing clear documentation and checklists for scalable, high-quality lesson improvement

## Folder Structure

- Each module contains subfolders for each lesson, with:
	- `original-lesson/`: The original HTML lesson file(s)
	- `new-lesson-output/`: The upgraded lesson, resource files, and checklist
		- `Files/`: Images, transcripts, and other lesson-specific resources
		- `lesson-resources.json`: Structured enrichment links, practice questions, career connections, and branding guidelines
		- `lesson-upgrade-checklist.md`: Checklist and guidance for resource preparation and upgrade

## Upgrade Workflow

1. **Resource Preparation**: Complete the `lesson-upgrade-checklist.md` for each lesson, gathering images, transcripts, assessment items, and other resources.
2. **Content Analysis**: Review original lesson content, including video transcripts and assessment data, to identify gaps and opportunities for improvement.
3. **Lesson Upgrade**: Apply the new HTML theme, add CidiLabs interactivity, and enrich content using the prepared resources and best practices.
4. **JSON Resource File**: Populate `lesson-resources.json` with enrichment links, practice questions, career connections, and accessibility/branding notes.
5. **Quality Review**: Ensure all starred LOs are fully addressed, and that the lesson meets accessibility, engagement, and instructional standards.

## What Goes in the JSON File?

**Include:**
- Enrichment links (URLs, descriptions)
- Practice questions (with answers)
- Career connections (summaries, talking points)
- Branding/accessibility guidelines (key requirements)
- Brief instructor/institutional notes (if lesson-specific)

**Keep as separate files:**
- Images, diagrams, and media (in `Files/`)
- Full assessment/test banks (unless short)
- Detailed interactive scripts (if complex)

## Contributor Guidance

- Use the `lesson-upgrade-checklist.md` in each lesson’s `new-lesson-output` folder to ensure all resources are ready before upgrade.
- Place all images, transcripts, and supporting files in the lesson’s `Files/` folder.
- Use structured JSON for non-image resources to enable automation and consistency.
- Document any unique requirements or preferences in the checklist or JSON file.

---

# Lesson Learning Objectives Coverage

## M1L1 Significant Figures and Scientific Notation: Current Status & Next Steps

- **Last updated:** January 10, 2026
- **Status:**
	- Lesson content and practice problems upgraded to new HTML theme.
	- Strict answer formatting callout added before Practice and Apply section.
	- CidiLabs sort tool activity present but currently unusable due to known bug (see Known Issues).
- **Next Steps:**
	- Review lesson for further assessment alignment or improvements as needed.
- **Notes:**
	- See new interactive project repo (link to be added when available).
	- Do not use CidiLabs sort until bug is fixed or replaced.

This document summarizes which Learning Objectives (LOs) are explicitly covered (starred) in each lesson HTML file. Lessons without a starred LO are noted.

| Lesson | Starred Learning Objectives (LOs) |
|--------|-----------------------------------|
| M1L1 Significant Figures and Scientific Notation | ★ LO1.1.2 Apply the rules of significant figures |
| M1L2 SI and Imperial Units | ★ LO1.1.3 Identify SI and imperial units<br>★ LO1.1.4 Match the SI prefixes with their corresponding values |
| M2L1 Stars | ★ LO2.1.1 Determine the origin of stars and their life cycle<br>★ LO2.1.2 Perform computations involving a star’s brightness, color, and temperature |
| M2L2 Galaxies | ★ LO2.1.3 Identify galaxy properties<br>★ LO2.1.4 Identify properties and predictions of the Big Bang theory |
| M3L1 Planets in Our Solar System | ★ LO3.1.1 Describe each of the planets in the solar system |
| M3L2 Comets, Asteroids, and Meteors | ★ LO3.1.2 Distinguish between comets, asteroids, and meteors in the solar system |
| M3L3 Origins of Our Solar System | ★ LO3.1.3 Describe the origins of the solar system |
| M4L1 The Motion of Earth | ★ LO4.1.1 Identify the Earth’s shape and size<br>★ LO4.1.2 Describe the different types of Earth’s motion<br>★ LO4.1.3 Contrast latitude and longitude<br>★ LO4.1.4 Perform calculations with time on Earth |
| M4L2 The Earth and Moon | ★ LO4.1.5 Identify the phases of the Moon<br>★ LO4.1.6 Determine the effects of the Moon on the Earth |
| M5L1 Motion | ★ LO5.1.1 Compare and contrast the different types of motion<br>★ LO5.1.2 Draw displacement, velocity, and acceleration vectors of moving objects<br>★ LO5.1.3 Solve problems involving kinematic equations<br>★ LO5.1.4 Draw and compute centripetal acceleration of an object undergoing uniform circular motion |
| M5L2 Forces | ★ LO5.2.1 Describe and quantify the different types of forces<br>★ LO5.2.2 Solve problems using Newton’s Laws of Motion<br>★ LO5.2.3 Draw force-body diagrams<br>★ LO5.2.4 Perform computations uses force and acceleration<br>★ LO5.2.5 Identify when momentum is and is not conserved<br>★ LO5.2.6 Compute impulse from an applied force |
| M6L1 Work & Energy | ★ LO6.1.1 Calculate work from displacement and net force<br>★ LO6.1.2 Distinguish between conservative and non-conservative forces<br>★ LO6.1.3 Compute kinetic energy and potential energy due to gravity<br>★ LO6.1.4 Identify different ways in which energy is stored<br>★ LO6.1.5 Compute the total energy, and changes in energy of a system |
| M7L1 Temperature and Thermal Energy | ★ LO7.1.1 Perform unit conversions between kelvin, degrees Celsius, and degrees Fahrenheit<br>★ LO7.1.2 Investigate the meaning of thermal equilibrium<br>★ LO7.1.3 Compute the expansion of heated or cooled objects |
| M7L2 States of Matter and Ideal-Gas Law | ★ LO7.1.4 Compare and contrast the different states of matter<br>★ LO7.1.5 Practice using the ideal gas law to find the state of an ideal gas |
| M7L3 Heat | ★ LO7.1.6 Differentiate between thermal energy, temperature, and heat<br>★ LO7.1.7 Solve problems involving heat transfer, specific heat, and latent heat |
| M7L4 Machines | ★ LO7.1.8 Create machine diagrams and perform calculations from them |
| M8L1 The Atmosphere | ★ LO8.1.1 Analyze the composition, structure, and pressure of the atmosphere<br>★ LO8.1.2 Solve problems using the pressure-volume equation<br>★ LO8.1.3 Correlate the role of wind and water in the atmosphere<br>★ LO8.1.4 Solve the change in temperature of soil caused by the sun shining |
| M9L1 Clouds, Precipitation, and Storms | ★ LO9.1.1 Analyze the types cloud-forming processes and the origin of precipitation<br>★ LO9.1.2 Describe the major storms formed on Earth |
| M9L2 Climate Change | ★ LO9.1.3 Describe climate change and its causes |

**Note:**
- All lessons now have at least one starred LO.
- Starred LOs (★) indicate the lesson contains content related to that objective.

---

## Lesson Coverage Analysis: Do Lessons Meet Their Indicated Learning Objectives?

Below is an analysis of whether each lesson's original content adequately covers the indicated (starred) learning objectives (LOs). Lessons needing updates are clearly noted.

### Module 1: Principles of Science

**M1L1 Significant Figures and Scientific Notation**
- Starred LO: ★ LO1.1.2 Apply the rules of significant figures
- **Coverage:** Lesson includes detailed rules, examples, and a video on significant figures. **Adequate.**

**M1L2 SI and Imperial Units**
- Starred LOs: ★ LO1.1.3, ★ LO1.1.4
- **Coverage:** SI/imperial units, prefixes, interactive activities, and prompts. **Adequate.**

### Module 2: The Universe

**M2L1 Stars**
- Starred LOs: ★ LO2.1.1, ★ LO2.1.2
- **Coverage:** Star formation, life cycle, brightness, color, temperature, and practice. **Adequate.**

**M2L2 Galaxies**
- Starred LOs: ★ LO2.1.3, ★ LO2.1.4
- **Coverage:** Galaxy properties, Big Bang theory, images, and videos. **Adequate.**

### Module 3: The Solar System

**M3L1 Planets in Our Solar System**
- Starred LO: ★ LO3.1.1
- **Coverage:** Descriptions, models, videos, and interactive content for each planet. **Adequate.**

**M3L2 Comets, Asteroids, and Meteors**
- Starred LO: ★ LO3.1.2
- **Coverage:** Differences between comets, asteroids, meteors, NASA resources, and video. **Adequate.**

**M3L3 Origins of Our Solar System**
- Starred LO: ★ LO3.1.3
- **Coverage:** Formation of the solar system, video, and practice prompts. **Adequate.**

### Module 4: The Earth

**M4L1 The Motion of Earth**
- Starred LOs: ★ LO4.1.1, ★ LO4.1.2, ★ LO4.1.3, ★ LO4.1.4
- **Coverage:** Earth's shape, motion, latitude/longitude, time calculations, videos, and diagrams. **Adequate.**

**M4L2 The Earth and Moon**
- Starred LOs: ★ LO4.1.5, ★ LO4.1.6
- **Coverage:** Moon phases, effects of the Moon, NASA resources, and videos. **Adequate.**

### Module 5: Motion and Forces

**M5L1 Motion**
- Starred LOs: ★ LO5.1.1, ★ LO5.1.2, ★ LO5.1.3, ★ LO5.1.4
- **Coverage:** Types of motion, vectors, kinematic equations, circular motion, and practice problems. **Adequate.**

**M5L2 Forces**
- Starred LOs: ★ LO5.2.1, ★ LO5.2.2, ★ LO5.2.3, ★ LO5.2.4, ★ LO5.2.5, ★ LO5.2.6
- **Coverage:** Types of forces, Newton's Laws, momentum, impulse, videos, and practice. **Adequate.**

### Module 6: Work and Energy

**M6L1 Work & Energy**
- Starred LOs: ★ LO6.1.1, ★ LO6.1.2, ★ LO6.1.3, ★ LO6.1.4, ★ LO6.1.5
- **Coverage:** Work, energy, force, kinetic/potential energy, conservation, and practice. **Adequate.**

### Module 7: Heat and Temperature

**M7L1 Temperature and Thermal Energy**
- Starred LOs: ★ LO7.1.1, ★ LO7.1.2, ★ LO7.1.3
- **Coverage:** Temperature scales, conversions, thermal equilibrium, expansion, and practice. **Adequate.**

**M7L2 States of Matter and Ideal-Gas Law**
- Starred LOs: ★ LO7.1.4, ★ LO7.1.5
- **Coverage:** States of matter, ideal gas law, videos, and practice. **Adequate.**

**M7L3 Heat**
- Starred LOs: ★ LO7.1.6, ★ LO7.1.7
- **Coverage:** Thermal energy, heat transfer, specific/latent heat, and practice. **Adequate.**

**M7L4 Machines**
- Starred LO: ★ LO7.1.8
- **Coverage:** The lesson provides content on machine diagrams, heat engines, refrigerators, efficiency, and the Second Law of Thermodynamics, with video and diagram resources. **Adequate.**

### Module 8: The Atmosphere

**M8L1 The Atmosphere**
- Starred LOs: ★ LO8.1.1, ★ LO8.1.2, ★ LO8.1.3, ★ LO8.1.4
- **Coverage:** Atmospheric composition, pressure, wind, water, temperature, and NOAA resources. **Adequate.**

### Module 9: Weather and Climate

**M9L1 Clouds, Precipitation, and Storms**
- Starred LOs: ★ LO9.1.1, ★ LO9.1.2
- **Coverage:** Cloud formation, precipitation, storms, videos, and interactive activities. **Adequate.**

**M9L2 Climate Change**
- Starred LO: ★ LO9.1.3
- **Coverage:** Climate change science, greenhouse effect, stratospheric cooling, and practice. **Adequate.**

---

### Summary of Lessons Needing Updates

All lessons have content that adequately covers their indicated (starred) learning objectives.
