# XML Language

## Overview
XML (eXtensible Markup Language) is used to store and transport data. It is both human-readable and machine-readable. XML is commonly used in Android layouts, web services, configuration files, and data exchange.

---

## Features
- Self-descriptive tags
- Platform and language independent
- Hierarchical (tree-based) structure
- Supports Unicode
- Custom user-defined tags
- Used widely for configuration and data transfer

---

## Basic Syntax Example

```xml
<?xml version="1.0" encoding="UTF-8"?>
<note>
    <to>John</to>
    <from>Alice</from>
    <heading>Reminder</heading>
    <message>Don't forget our meeting tomorrow!</message>
</note>
```

## Syntax Rules

<li>Root element is required: <root> ... </root></li>

<li>Tags are case-sensitive: <Name>John</Name></li>

<li>All tags must be closed: <tag>value</tag></li>

<li>Attributes must use quotes: <user id="101" status="active"></user></li>

<li>Escape special characters: & → &amp;, < → &lt;, > → &gt;, " → &quot;, ' → &apos; </li>

XML vs HTML
Feature	XML	HTML
Purpose	Data storage/transport	Display content
Tags	User-defined	Predefined
Case-sensitive	Yes	No
Error handling	Strict	Lenient
Structure	Hierarchical	Document-based
