# C2111C3 Web Technologies Course Portal

A static, responsive course website for the Web Technologies subject (C2111C3) at ITMBU B.Tech CSE. It provides a central course portal, a syllabus overview, and detailed study guides for all six units.

## Pages

| Page | Description |
|---|---|
| [`course_portal.html`](course_portal.html) | Main portal with unit tabs and links to all course resources |
| [`Syllabus.html`](Syllabus.html) | Course objectives, unit summary, contact hours, and assessment topics |
| [`unit1_intro_to_www.html`](unit1_intro_to_www.html) | Internet and WWW concepts, HTTP, browsers, servers, Web 2.0, Linux hosting, dynamic IP, and web design |
| [`unit2_html.html`](unit2_html.html) | HTML elements, attributes, links, lists, tables, images, forms, semantic HTML5, multimedia, and metadata |
| [`unit3_css_final.html`](unit3_css_final.html) | CSS syntax, selectors, text and typography, the box model, borders, positioning, and layouts |
| [`unit4_javascript_jquery.html`](unit4_javascript_jquery.html) | JavaScript basics, DOM interaction, functions, objects, events, form validation, AJAX, and jQuery |
| [`unit5_xml.html`](unit5_xml.html) | XML structure, DTD, XML Schema, DOM and SAX processing, namespaces, XSL, and XSLT |
| [`unit6_php.html`](unit6_php.html) | Server-side scripting, PHP syntax, strings, regular expressions, frameworks, and PHP examples |

## Features

- Central unit navigation with URL hash support
- Linked detailed study guides for every unit
- Topic-level in-page navigation
- Responsive layouts for desktop and mobile screens
- Print and browser PDF export buttons
- Reduced-motion support for accessibility
- Internal cross-links and external reference links
- Standalone HTML pages with no build step or package installation required

## Getting Started

### Open directly

Open [`course_portal.html`](course_portal.html) in a web browser.

### Run a local server

Using Python:

```bash
cd "Web Technologies - C2111C3 Notes"
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/course_portal.html
```

Alternatively, use the Live Server extension in VS Code and open `course_portal.html`.

## Project Structure

```text
Web Technologies - C2111C3 Notes/
├── README.md
├── course_portal.html
├── Syllabus.html
├── unit1_intro_to_www.html
├── unit2_html.html
├── unit3_css_final.html
├── unit4_javascript_jquery.html
├── unit5_xml.html
└── unit6_php.html
```

## Navigation

Start with the course portal. Use the unit tabs to switch between topics or use the resource links to open each detailed study guide.

The portal supports direct unit links in this format:

```text
course_portal.html#unit1
course_portal.html#unit2
course_portal.html#unit3
course_portal.html#unit4
course_portal.html#unit5
course_portal.html#unit6
```

## PDF Download

Each detailed study guide includes a **Download as PDF** button. The button opens the browser print dialog; select **Save as PDF** to export the guide.

## PHP Examples

The PHP guide is also a static HTML document. PHP code shown in the guide is instructional and is not executed by this website.

To run a PHP example, install PHP and start a local PHP server in the example directory:

```bash
php -S localhost:8000
```

Then open the PHP file through `http://localhost:8000/` rather than through a `file://` URL.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Responsive CSS and media queries
- Browser print API

## Browser Compatibility

The pages use standard HTML, CSS, and JavaScript and can be viewed in current versions of Chrome, Edge, Firefox, and Safari.

## Maintenance

Keep the HTML files in the same folder so relative navigation links continue to work. When adding a new page:

1. Add it to the portal resource navigation.
2. Add navigation links to the other course pages.
3. Use heading IDs for topic-level anchors.
4. Test links and layouts at desktop and mobile widths.
