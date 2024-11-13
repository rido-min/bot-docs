---
title: Architecture
description: "Learn about the Blah Architecture."
author: sarahcritchley
ms.author: scritchley
manager: kjette
ms.reviewer: cyanderson
ms.topic: overview
ms.date: 11/07/2024
---

# Architecture

<pre class="mermaid">
graph TD
    A[Presentation Layer] --> B[Business Logic Layer]
    B --> C[Data Access Layer]
</pre>

<script type="module">
	import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
	mermaid.initialize({
		startOnLoad: true,
		theme: 'dark'
	});
</script>