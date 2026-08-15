---
title: "Digital Train Signage for PATH"
description: "Public-facing signage system delivering updates within 100&nbsp;ms, built to a four-month timeline."
slug: "Digital Train signage"
weight: 90
date: 2019-09-19

# Catalog fields. These drive the parts table on /products/ and the spec
# block on the product page - do not repeat them in the body copy.
# TODO: this product's part number was a copy of the CD20 shelf's in the
# previous content; left blank until the correct number is confirmed.
partNumber: ""
mounting: ""
rackUnits: ""
cutSheet: ""
category: "Software & systems"
---
In 2018 we took on the Digital Signage project for the Path trains. Our software parses the entirely custom binary format provided by the reporting systems and sends updates to the signage within 100 milliseconds. As a piece of public facing infrastructure we followed a disaster recovery protocol where over half of the machines in our system can go down and the system remains fully functional.

Our signage features included:

    . Multiple easy to configure layouts for different sized displays
    . Interfaces to change scrollings text, and to override an
    entire sign
    . A user management system with a full audit trail to allow any
    operator manage the signs
    . Lightweight APIs which feed data to both the signage and mobile
    applications

This project was delivered in a strict 4 month timeline. Since launching the product we can proudly say there have been ZERO bugs.

{{< carousel images="{gallery/*.jpg}" >}}
