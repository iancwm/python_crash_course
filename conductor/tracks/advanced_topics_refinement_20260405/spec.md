# Specification: Improve Advanced Topics Instructional Quality and Depth

## 1. Overview

This track focuses on comprehensively rewriting and expanding the Advanced Topics notebooks (Sessions 6-8) to match and exceed the quality bar set by the refined Sessions 1-5. The goal is to provide deeper, more practical examples, update all code for Python 3.12+ and modern library versions, and ensure each notebook follows the established product guidelines (informal prose, clean aesthetic, interactive structure).

All external data dependencies (especially Google Drive references) must be removed. Notebooks should be fully self-contained or use publicly accessible datasets that work without authentication.

## 2. Goals

- Deliver fully rewritten Session 6 (Regex), Session 7 (NumPy), and Session 8 (pandas) notebooks with expanded content and deeper examples
- Update all code examples to be compatible with Python 3.12+ and current versions of NumPy, pandas, and related libraries
- Remove all Google Drive references and external data dependencies
- Add interactive test cells throughout each notebook to verify key concepts
- Ensure prose is informal, engaging, and follows the clean/minimalist aesthetic
- Apply Google Python Style Guide consistently across all code blocks

## 3. Scope

### In Scope
- `Session 6 - Advanced Topics - Regular Expressions.ipynb`
- `Session 7 - Advanced Topics - Numpy.ipynb`
- `Session 8 - Advanced Topics - pandas.ipynb`

### Out of Scope
- Project notebooks (Pokemon EDA, Cannabis Classification, Bank Churn)
- Sessions 1-5 (already completed)
- New session creation beyond the three advanced topics

## 4. Functional Requirements

1. Each notebook must contain interactive test cells (assert-based) after key concept sections
2. Code examples must use Python 3.12+ compatible syntax
3. Library-specific code must use current API patterns (e.g., pandas 2.x, numpy 1.26+)
4. Prose must follow product guidelines: informal, engaging, clear
5. All code must follow Google Python Style Guide
6. No Google Drive references or authentication-dependent data sources

## 5. Acceptance Criteria

- All three notebooks are fully rewritten with expanded content
- Test cells pass without errors
- No deprecated API usage (e.g., no `append` in pandas, no old numpy patterns)
- No Google Drive references remain in any notebook
- Code style is consistent with Google Python Style Guide
- Notebook structure encourages interactive exploration
