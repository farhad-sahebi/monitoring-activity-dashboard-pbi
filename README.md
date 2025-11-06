# Monitoring Activity Dashboard (Power BI)

A professional Power BI dashboard to track **site visit monitoring** across projects and provinces. It consolidates planned, completed, and cancelled visits, with dynamic slicers for Province, District, Project, Visit Status, Reporting Type, and Planned Field Work Period.

<p align="center">
  <img src="docs/images/page1-overview.png" alt="Monitoring Overview" width="90%">
</p>

## Highlights
- **Interactive monitoring by location type** (entity categories)
- **Monthly & planned monitoring by project** (column/line toggle)
- **Province map** showing density of visits
- **Gender disaggregation** for respondents & monitoring staff
- Professional **slicers** for deep filtering and analysis

## Key Metrics 
- **Completed Visits:**
- **Cancelled Visits:**  
- **Planned Visits:**  

## Pages
1. **Project Monitoring** – monthly trends by project, map by province, plan vs. actual  
2. **Respondents & Monitoring Staff** – gender disaggregation visuals

<p align="center">
  <img src="docs/images/page2-gender-breakdown.png" alt="Gender Disaggregation" width="90%">
</p>

## 🛠 Data & Model
- **Source:** Site-visit records (project, location, entity type, status, dates)  
- **Modeling:** Cleaned with Power Query; key DAX measures for totals and period trends  
- **Entity Types:** Energy, Water Resource Management, Government Agencies, Multinational Collaboration, Maritime & Port Authority, etc.

> See full write-ups:  
> - [`docs/dashboard-description.md`](docs/dashboard-description.md)  

## Sample Data
A de-identified sample is included in `data/sample/` for structure reference. Replace with real data as needed.

## File Structure
pbix/ # Power BI files and themes
docs/ # Documentation + images
data/ # Sample data + dictionary
src/ # (Optional) DAX/Power Query exports


## How to Use
1. Open `pbix/Monitoring-Activity-Dashboard.pbix` in Power BI Desktop.
2. Update data source paths if prompted.
3. Refresh to load latest data.
4. Use slicers to filter by geography, project, and status.

## Visual/UX Notes
- Clean card KPIs, rounded containers, soft shadows
- Toggle button to switch column/line chart for Monthly by Project
- Province map color scale: 1–100 / 101–200 / 201–400+

## Data & Ethics
- No PII is included. Sample data is anonymized.
- Real datasets should follow your organization’s data governance & consent rules.

## Roadmap
- [ ] Add automated monthly snapshot images to `/docs/images/`
- [ ] Publish to Power BI Service & embed read-only link in README
- [ ] Add unit tests for DAX with Tabular Editor Best Practice Analyzer (optional)

## 📄 License
MIT – see [`LICENSE`](LICENSE).

## Author
**Mohammad Farhad Sahebi** – Data Analyst  
Connect: LinkedIn | GitHub
Connect: [LinkedIn](https://linkedin.com/in/farhad-sahebi) | [GitHub](https://github.com/farhad-sahebi)







