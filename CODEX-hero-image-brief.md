# Codex Task: Generate Hero Images for biosecuritytraining.nz

## Your Task
Generate hero images for all 6 pages of the biosecuritytraining.nz website using DALL-E 3 (or equivalent image generation API). Save each image in both JPG and WebP formats to the path specified below.

---

## Save Location
Save all images to:
```
/Users/capabilitysolutions/Desktop/My Gemini CCOS Workspace/biosecuritytraining.nz/images/
```
Create the `images/` directory if it does not exist.

---

## Output Format Requirements (SEO-Critical)

Generate **two versions of each image**:

| Version | Format | Use |
|---|---|---|
| `hero-[name].jpg` | JPG, 80% quality | Fallback for older browsers |
| `hero-[name].webp` | WebP, 80% quality | Primary — faster load, better Core Web Vitals |

- **Dimensions:** 1440 × 500 pixels
- **Target file size:** Under 200KB per image (JPG), under 120KB (WebP)
- **Compression:** Apply lossless optimisation after generation if possible
- **DO NOT upscale** — generate at native size or downscale, never upscale

> Page speed is a direct Google ranking signal. Oversized hero images will hurt Core Web Vitals and SEO. Keep files tight.

---

## Global Style Rules — Apply to Every Image

- **Style:** Photorealistic, professional, editorial photography style
- **Setting:** New Zealand warehouse, freight terminal, logistics facility, or cold storage environment — Auckland-feel, modern, operational
- **People:** Mix of Euro NZ and Pasifika NZ people. Typical Auckland workforce. Diverse ages. Professional but approachable.
- **NO hard hats** — hi-vis vests are fine, but no hard hats on anyone
- **NO government logos, MPI branding, official signage, or regulatory insignia** in any image
- **NO stock-photo clichés** — no people staring directly at the camera, no forced smiles, no handshakes in front of clipboards
- **Lighting:** Natural industrial lighting, daylight where possible, warm and professional
- **Mood:** Competent, operational, trustworthy — not sterile or corporate

---

## Images to Generate

Each image listing includes:
- **Prompt** — the generation instruction
- **Alt text** — the exact text to use in the HTML `alt=""` attribute (SEO + accessibility + AI indexing)
- **OG description** — used in Open Graph and Twitter Card meta tags

---

### 1. Home Page Hero
**Filename:** `hero-home.jpg` / `hero-home.webp`

**Prompt:**
Wide establishing shot inside a large, modern New Zealand warehouse or freight distribution centre. A small group of workers — two Euro NZ and one Pasifika NZ — are moving through the facility, one reviewing a tablet, another directing a forklift in the background. Hi-vis vests, no hard hats. Floor-level perspective, wide angle. Industrial fluorescent lighting overhead, loading bay doors open to daylight in background. No signage or logos visible. Clean, well-organised facility. Photorealistic editorial photography, 1440x500px banner crop.

**Alt text:**
`New Zealand warehouse team managing biosecurity-compliant freight operations`

**OG description:**
`New Zealand's biosecurity training resource — free courses, AP accreditation, and the Biosecurity Business Pledge.`

---

### 2. Article: NZ Biosecurity for Businesses
**Filename:** `hero-nz-biosecurity-for-businesses.jpg` / `hero-nz-biosecurity-for-businesses.webp`

**Prompt:**
Inside a modern Auckland warehouse office or mezzanine overlooking a busy warehouse floor. A mid-40s Pasifika NZ woman and a younger Euro NZ man are reviewing documents or a laptop together at a standing desk. Business casual attire. The warehouse floor is visible below through glass — forklifts, racking, pallet stacks. Natural light from skylights. Professional, engaged expressions. No logos or signage visible. Photorealistic editorial photography, 1440x500px banner crop.

**Alt text:**
`NZ business managers reviewing biosecurity compliance obligations in a warehouse office`

**OG description:**
`New Zealand's biosecurity system protects a $50B economy. Find out what it means for your business and what you need to do.`

---

### 3. Article: What is an Accredited Person (AP)?
**Filename:** `hero-accredited-person-ap.jpg` / `hero-accredited-person-ap.webp`

**Prompt:**
A professional NZ freight worker — mid-30s Euro NZ man — in a hi-vis vest (no hard hat) is carefully inspecting the exterior of a large intermodal shipping container at a New Zealand container yard or cold store facility. He is holding a clipboard or tablet and examining the container seals closely. Wide shot, container yard context visible in background with stacked containers. Daylight, overcast NZ sky. Focused, methodical. No government logos or MPI branding anywhere. Photorealistic editorial photography, 1440x500px banner crop.

**Alt text:**
`MPI Accredited Person inspecting an imported shipping container at a New Zealand transitional facility`

**OG description:**
`An Accredited Person (AP) is authorised by MPI to carry out biosecurity activities in New Zealand. Find out who needs one and how to become one.`

---

### 4. Article: What is the Biosecurity Business Pledge?
**Filename:** `hero-biosecurity-business-pledge.jpg` / `hero-biosecurity-business-pledge.webp`

**Prompt:**
A small group of four business professionals in a modern Auckland boardroom or glass-walled meeting room. Mix: one Pasifika NZ woman (50s, senior), one Euro NZ man (40s), one younger Pasifika NZ man, one Euro NZ woman (30s). Business attire. They are engaged in a collaborative discussion around a table with papers and a laptop. Warm natural light from floor-to-ceiling windows overlooking a cityscape or port. No handshakes or forced corporate poses — natural conversation. No logos visible. Photorealistic editorial photography, 1440x500px banner crop.

**Alt text:**
`New Zealand business leaders meeting to discuss biosecurity risk management commitments`

**OG description:**
`The Biosecurity Business Pledge is a collective commitment by NZ businesses to lead biosecurity risk. Find out what signing means for your organisation.`

---

### 5. Article: QCONZ AP Biosecurity Training Course
**Filename:** `hero-qconz-ap-training-course.jpg` / `hero-qconz-ap-training-course.webp`

**Prompt:**
A mid-20s Pasifika NZ woman in a hi-vis vest is seated at a table in a warehouse break room or site office, working through a training course on a laptop or tablet. Natural, focused expression — engaged with the content. Coffee cup nearby. The warehouse environment is visible through a window or open door behind her — forklifts, racking. Warm, practical lighting. Feels real and relatable, not a staged stock photo. No hard hats, no government logos. Photorealistic editorial photography, 1440x500px banner crop.

**Alt text:**
`Warehouse worker completing the QCONZ MPI-approved Accredited Person online training course`

**OG description:**
`QCONZ delivers MPI-approved online AP training for sea container inspection at New Zealand transitional facilities. Full course, refresher, and free awareness training.`

---

### 6. Article: Site Access Management for Transitional Facilities
**Filename:** `hero-transitional-facility-site-access.jpg` / `hero-transitional-facility-site-access.webp`

**Prompt:**
The entrance point of a busy New Zealand freight facility or transitional facility. A Euro NZ security or site administrator — late 30s, hi-vis vest — is checking in an arriving contractor who is scanning a QR code on their phone at a site kiosk. A second worker is waiting behind, also in hi-vis. Modern, digital — the kiosk screen is clearly visible. Loading docks visible in background with a truck or container. Daytime, industrial setting. No hard hats, no government or MPI signage. Feels operational and current. Photorealistic editorial photography, 1440x500px banner crop.

**Alt text:**
`Contractor scanning QR code at NZ transitional facility entrance using SiteKey site access system`

**OG description:**
`MPI Approved Transitional Facilities face biosecurity, health and safety, and aviation security obligations. SiteKey and AirCertifyNZ help manage them.`

---

## After Generating All Images

1. Confirm all 12 files (6 JPG + 6 WebP) are saved to the `images/` directory
2. Report the filename and file size of each
3. Do NOT modify any HTML files — image integration will be handled separately

---

## Reference: Full HTML Integration Spec
*(For the developer who will embed these images)*

Each hero section needs:

```html
<!-- In <head>: preload the WebP for above-fold images -->
<link rel="preload" as="image" href="/images/hero-[name].webp" type="image/webp">

<!-- Open Graph tags in <head> -->
<meta property="og:image" content="https://biosecuritytraining.nz/images/hero-[name].jpg">
<meta property="og:image:width" content="1440">
<meta property="og:image:height" content="500">
<meta property="og:image:alt" content="[alt text from above]">
<meta name="twitter:image" content="https://biosecuritytraining.nz/images/hero-[name].jpg">

<!-- Hero background — replace current CSS gradient with: -->
<style>
  .hero, .article-hero {
    background:
      linear-gradient(rgba(0,59,73,0.72), rgba(0,59,73,0.72)),
      url('/images/hero-[name].webp') center/cover no-repeat;
  }
</style>

<!-- Visible <img> for AI indexing (hidden visually but in DOM) -->
<img
  src="/images/hero-[name].webp"
  alt="[alt text from above]"
  width="1440"
  height="500"
  loading="eager"
  fetchpriority="high"
  style="position:absolute;width:1px;height:1px;overflow:hidden;opacity:0;pointer-events:none;"
  aria-hidden="true"
>

<!-- Schema.org ImageObject in <script type="application/ld+json"> -->
{
  "@type": "ImageObject",
  "url": "https://biosecuritytraining.nz/images/hero-[name].jpg",
  "width": 1440,
  "height": 500,
  "description": "[alt text from above]"
}
```

### Per-page image map

| Page | WebP file | JPG fallback | Alt text |
|---|---|---|---|
| `index.html` | `hero-home.webp` | `hero-home.jpg` | New Zealand warehouse team managing biosecurity-compliant freight operations |
| `nz-biosecurity-what-every-business-needs-to-know.html` | `hero-nz-biosecurity-for-businesses.webp` | `.jpg` | NZ business managers reviewing biosecurity compliance obligations in a warehouse office |
| `what-is-an-accredited-person-ap-new-zealand.html` | `hero-accredited-person-ap.webp` | `.jpg` | MPI Accredited Person inspecting an imported shipping container at a New Zealand transitional facility |
| `what-is-the-biosecurity-business-pledge.html` | `hero-biosecurity-business-pledge.webp` | `.jpg` | New Zealand business leaders meeting to discuss biosecurity risk management commitments |
| `qconz-ap-biosecurity-training-course.html` | `hero-qconz-ap-training-course.webp` | `.jpg` | Warehouse worker completing the QCONZ MPI-approved Accredited Person online training course |
| `site-access-management-for-transitional-facilities-sitekey.html` | `hero-transitional-facility-site-access.webp` | `.jpg` | Contractor scanning QR code at NZ transitional facility entrance using SiteKey site access system |
