# Code Refactor Starter Code
url:
https://zacktmiller92.github.io/rutgers-bootcamp-challenge-1/index.html

Screenshot: 
![website screenshot](assets/images/screenshot.png)

## Overview
Client requested we update their website to follow html5 accessibility standards. Below are the changes made, along with some additional edits to improve readability for future development work. 

### Head Section
- Changed title tag to reflect the brand name. 

### Navigation Section
- changed container div tag to nav tags
- wrapped in semantic header tag
- removed head class from nav tag (more details in CSS section)

### Hero Section
- changed container div tag to nav tag

### Services Section
- changed container div tag to section tag
- changed service containers to article tags
- added id to article tag for "search engine optimization" service
- added alt tags to images
- renamed class from "content" to "services" to be more readable
- consolidated classes in css and updated them in the html

### Benefits Section
- changed container div tag to aside tag
- changed benefit containers to article tags
- added alt tags to images
- nested in aside tag

### Footer Section
- changed container div tag to footer tag
- removed footer class

### CSS
#### General Updates To Structure
- organized declarations and grouped them by sections
- sections are denoted by comments
#### Services Section
- renamed content class to services class
- consolidated search-engine-optimization, online-reputation-management, social-media-marketing declarations to 'service-item' class
- consoidated css declarations for img elements in services section
- consolidated css declarations for h2 elements in services section

#### Header Section
- rewrote css to target header tag instead header class
#### Benefits Section
- consolidated benefit-lead, benefit-brand & benefit-cost declarations to 'benefit' class
- consoidated css declarations for h3 elements in benefit section
- consolidated css declarations for img elements in benefit section
#### Footer Section
- updated footer selectors to target footer tags instead of footer class