# Portfolio Audit vs. Cornell Lab Data Visualization Developer JD

## Executive Summary

The portfolio is well-positioned for this role. The title match is exact, the Cornell Lab work is prominent, and core required skills (Mapbox, d3, Highcharts, R, Vue/Nuxt, Git, AWS S3) are present. The main gaps are **missing tool names that the JD explicitly calls out**, **process/soft-skill language that the JD heavily weights**, and **commented-out content** that should be visible.

---

## Gaps: Required Qualifications Not Reflected in Portfolio

### High Priority — JD uses these exact terms

| Missing Item | Where It Appears in JD | Fix |
|---|---|---|
| **Tippecanoe** | Preferred qualifications, Data Management responsibilities | Add to Skills list |
| **Testing and documentation** | Required: "Proven experience documenting and testing code" | Add to Skills or project descriptions |
| **Web performance, scaling, deployment** | Required: "Basic understanding of web performance, scaling, and deployment" | Add to Skills or bio |
| **Bootstrap / Material** | Preferred qualifications | Currently commented out in HTML — restore |
| **Angular** | Required (Vue, Nuxt, or Angular) | Currently commented out in project descriptions — restore |
| **TypeScript** | Implied by modern frontend best practices JD calls out | Currently commented out — restore |
| **Component libraries / modularity** | Preferred: "component libraries and code development focused on modularity and re-usability" | Not mentioned anywhere |
| **API / web services** | 5% of role: "web services and APIs that serve data to web-based visualizations" | Not mentioned anywhere |
| **GitLab / BitBucket** | Required: "GitHub, GitLab, or BitBucket" | Currently commented out in HTML — restore or add |

### Medium Priority — JD concepts present but underrepresented

| Gap | Notes |
|---|---|
| **Birds / ecology passion** | JD: "An interest in birds, nature, biology, science, and/or conservation is highly desired." Bio doesn't say this explicitly — Cornell work implies it but a direct line would strengthen fit. |
| **Raster data / geoprocessing** | JD repeatedly mentions raster data (vector tiles, Tippecanoe, `terra`, `stars`). Only one project (eBird) mentions raster geoprocessing, and the tech stack is commented out. |
| **Full development pipeline** | JD: "participates in the entire software development pipeline, from raw data processing... to deployment." Bio says "dashboards and data-driven decision support tools" but doesn't describe the full pipeline. |
| **Team collaboration** | JD mentions cross-functional team (designers, devs, GIS, statisticians, ecologists) in almost every responsibility block. Portfolio has no explicit collaboration language. |
| **Decision-support tools** | Bio mentions "data-driven decision support tools" — this maps well to JD preferred qualifications but could be more prominent. |
| **Human-computer interaction / UX** | JD: "Understanding of human-computer interactions and the design of interactive displays." Portfolio doesn't mention UX or accessibility. |

---

## Commented-Out Content That Should Be Restored

In `index.html`, several key tech stack items are commented out across project descriptions and the skills list. These are all explicitly required or preferred in the JD:

```
Bootstrap, Material         → Preferred qualifications
Angular                     → Required qualifications (explicit)
TypeScript                  → Modern frontend best practices
jQuery                      → In commented skills
BitBucket, GitLab           → Required (git interfaces)
```

Restore these — they are exact keyword matches against the JD requirements checklist.

---

## Project-Level Suggestions

### Yellow-bellied Sapsucker Abundance
- **Good:** Mobile-first design, raster geoprocessing to hex, map interactivity
- **Add:** Mention R packages used (`sf`, `terra`, or similar), Angular framework (currently commented out), and what specific challenge the raster-to-hex geoprocessing solved

### eBird Status and Trends
- **Good:** Scale (2900+ species), non-expert audience, professional context
- **Add:** Restore the commented-out tech stack (R, Nuxt/Vue). Add language about team collaboration — this is a team product. Mention dynamic chart + map architecture, population statistics on the fly. Consider adding: Tippecanoe, vector tiles, performance at scale.
- This is the most directly relevant project; it deserves the most detail.

### North American Bird Declines
- **Good:** Science publication tie-in, scrollytelling, species-level storytelling
- **Add:** Tech stack. Mention that it targets a public audience (JD: "from science experts to the general public"). Calling out the connection to a peer-reviewed publication is strong — lean into it.

### Basketball Travel Distance
- **Good:** "entire project lifecycle, including ideation, wireframing, data munging, and project execution" — this directly mirrors JD language about the full pipeline
- **Keep this language.** It's the best process-language in the portfolio.
- **Add:** Tech stack. Consider mentioning any documentation or testing practices used.

---

## Header / Bio Suggestions

### Current bio:
> "I'm a geographer-turned-software developer with expertise in interactive web maps. I build dashboards and data-driven decision support tools that bring clarity to difficult data. My goal is to present data in a clear, concise, and beautiful way that allows people to derive insights without any technical expertise. I currently work as a Data Visualization Developer at Cornell Lab of Ornithology."

### What's missing:
1. **Full pipeline language** — JD weights "from raw data processing... to designing and wireframing... to coding... to deployment" heavily. The bio only covers the end product.
2. **Team collaboration** — almost every JD responsibility block mentions working with a cross-functional team.
3. **Ecological data / birds** — the JD calls this "highly desired." This is Lauren's actual job; it just isn't stated.
4. **Geoprocessing** — JD explicitly calls out vector and raster geoprocessing. The bio mentions "interactive web maps" but not the data processing side.

### Suggested revision (draft):
> "I'm a geographer-turned-software developer specializing in interactive web maps and data-driven visualizations for ecology and conservation. I work across the full development pipeline — from geoprocessing raw spatial data (vector and raster) in R, to wireframing, building production web apps, and deployment. I build dashboards and decision-support tools that bring clarity to complex data for audiences ranging from domain experts to the general public. I currently work as a Data Visualization Developer at Cornell Lab of Ornithology, where I focus on eBird Status and Trends products."

---

## Skills Section Suggestions

### Current skills:
```
Web maps: Mapbox, vector tiles, GIS, H3, Turf.js
Data visualization: Highcharts, d3
Data processing and cloud: R, Python, AWS S3
Version control: Git
Javascript and front-end: Vue, Nuxt, jQuery, ES6
```

### Add:
```
Web maps: Mapbox GL JS, vector tiles, Tippecanoe, GIS, H3, Turf.js
Data visualization: Highcharts, d3
Data processing and cloud: R (sf, terra), Python, AWS S3
Version control: Git (GitHub, GitLab, BitBucket)
Javascript and front-end: Vue, Nuxt, Angular, TypeScript, jQuery, ES6, Bootstrap, Material
```

Key additions: **Tippecanoe** (JD calls it out three times), **R packages** (sf, terra — JD mentions these specifically), **Angular** (required), **TypeScript**, **Bootstrap/Material** (preferred), **GitLab/BitBucket** (required).

---

## Alignment Summary

| JD Category | Portfolio Coverage | Gap Level |
|---|---|---|
| Interactive web-based data viz | Strong | None |
| Web mapping (Mapbox, vector tiles) | Good | Add Tippecanoe |
| JS + viz libraries (d3, Highcharts) | Good | None |
| Front-end frameworks (Vue, Nuxt, Angular) | Good | Angular commented out |
| R/Python geoprocessing | Present | Needs more specificity |
| AWS S3 | Present | None |
| Git version control | Present | Add GitLab/BitBucket |
| Full dev pipeline (data → deploy) | Weak | Revise bio |
| Testing and documentation | Missing | Add explicitly |
| Team collaboration | Weak | Add to bio and projects |
| Web performance / deployment | Missing | Add to skills |
| Component libraries / modularity | Missing | Add to skills |
| API/web services | Missing | Add if applicable |
| Ecology/birds interest | Implied | Make explicit |
| Decision-support tools | Present (bio) | Good — keep |
| Mobile-first / multi-device | Present (one project) | Could be stronger |
