# Campus Multifamily Projects

The following is a summary of the proposed Revit best practices for PermitZIP multifamily projects that include multiple buildings and phases.

## 🏁 Planning

- Build the `🗽 BIM360 Model Structure` in `BIM 360` / **BIM Manager**
- Identify typicals / **Design Lead**
  - Coordinate with architect if possible.
  - Do this on a SINGLE shared pdf in a bluebeam session
- Create the Sheet List in `Host.rvt` / **Design Lead**

## 🏗 Revit Model Structure

![Proposed Complex Revit Model](../assets/images/modecture.png)

- **Master.rvt**
  - **Schedules** (modeled elements)
    - General Plan Notes
    - Plan Reference notes
    - Typical Mapping Schedule
  - **Plan Views**
    - Site
    - Details
    - Specifications
    - Typical Units
  - Phases (internal configuration)
- **BuildingN.rvt** (for each permit set)
  - **internal building infrastructure**
  - **links to other sheets / typical reference**
  - **general plan notes**
