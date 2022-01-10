# revit-best-practices

Proposed Revit best practices for PermitZIP

## Multi-Phase Multifamily Projects

### 🏁 Planning

- Build the `🗽BIM360 Model Structure` in `BIM 360` | **BIM Manager**
- Identify typicals | **Design Lead**
  - Coordinate with architect if possible.
  - Do this on a SINGLE shared pdf in a bluebeam session
- Create the Sheet List in `Host.rvt` | **Design Lead**

### 🗽BIM360 Model Structure

- Host.rvt
  - `Details, Specifications, Abbreviations, Notes`
    - using `legend views` allow a single detail on multiple sheets
  - `Project Phasing Overview`
    - Projevt Phases Overview as `legend view`
  - `Typicals.rvt`
    - Typicals as `plans views`
  - `Phase I.rvt`
    - Infrastructure as `plans views`
  - `Phase II.rvt`
    - Infrastructure as `plans views`
  - `Phase III.rvt`
    - Infrastructure as `plans views`
