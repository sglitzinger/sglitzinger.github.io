---
title: Fast Compression of Floating-Point Values with Exponent/Mantissa Shuffling
authors:
- Lena Oden
- Sebastian Litzinger
- Jörg Keller
date: '2025-05-14'
publishDate: '2024-08-19T12:43:31.655483Z'
publication_types:
- article-journal
publication: '*PARS-Mitteilungen*'
abstract: We investigate fast compression algorithms for vectors of floating-point values, as these
  frequently appear in numerical computations. Our proposal bases on Snappy yet uses a modified data
  layout. Use of data chunks allows parallel thread-based compression without loss of compression
  quality. Our proposal beats previous proposals and standard compression algorithms in compression
  ratio and/or speed. The gain in compression ratio and speed can be used to shorten communication
  phases, e.g., between CPUs and accelerators.
url_pdf: https://dl.gi.de/server/api/core/bitstreams/32b75dd8-e088-4a4c-a691-6efe2b729768/content
---
