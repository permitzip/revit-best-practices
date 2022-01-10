# Campus Multifamily Projects

Proposed Revit best practices for PermitZIP multifamily projects that include multiple buildings and phases.

## 🏁 Planning

- Build the `🗽BIM360 Model Structure` in `BIM 360` / **BIM Manager**
- Identify typicals / **Design Lead**
  - Coordinate with architect if possible.
  - Do this on a SINGLE shared pdf in a bluebeam session
- Create the Sheet List in `Host.rvt` / **Design Lead**

## 🗽BIM360 Model Structure

- **Host.rvt**
  - **Legend View**
    - using a `legend views` allows the same detail instance to show on multiple sheets. **do not duplicate details as copies!**
    - Example Information:
      - details
      - specifications
      - legend, abbreviations, notes
  - **Project Phase Overview**
    - Project Phases Overview as `legend view`
  - **Typicals.rvt**
    - Typicals as `plans views`
  - **Phase I.rvt**
    - Infrastructure as `plans views`
  - **Phase II.rvt**
    - Infrastructure as `plans views`
  - **Phase III.rvt**
    - Infrastructure as `plans views`
