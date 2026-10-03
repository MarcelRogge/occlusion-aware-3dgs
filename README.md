# Counting Contributions, Not Views: Occlusion-Aware Densification for 3D Gaussian Splatting (ACCV 2026)

Marcel Rogge, René Schuster, Didier Stricker

## Overview
Adaptive density control gathers per-Gaussian statistics behind a frustum-based
visibility filter that is blind to occlusion: fully occluded Gaussians still count
as observed, which dilutes the averaged gradient and suppresses densification
exactly where geometry is seen through occlusions. We replace the filter with an
occlusion-aware one and replace the criterion's raw view-count normalizer with an
average-contribution normalizer.

## Status
🚧 Code release in preparation. 
