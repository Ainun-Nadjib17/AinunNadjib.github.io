# 29. 3D Element System

> **IMPORTANT**
>
> Elemen 3D adalah **enhancement layer** di atas design yang sudah ada.
>
> Elemen 3D tidak boleh menggantikan content atau component existing.
>
> Jika sebuah 3D element berpotensi mengganggu readability, interaction, atau layout, maka 3D element harus diposisikan sebagai decorative/background element.

---

## 29.1 3D Visual Language

Semua elemen 3D harus mengikuti bahasa visual:

* Cybernetic
* Futuristic
* Technical
* Military/HUD inspired
* Neural computing
* Cryptographic
* Procedural
* Dark metallic
* Holographic

Hindari gaya:

* Cartoon
* Toy-like
* Cute
* Low-poly game asset
* Generic corporate 3D
* Colorful rainbow 3D

3D harus terlihat seperti **advanced technology interface / command system**.

---

# 30. Primary 3D Objects

Gunakan beberapa elemen 3D yang relevan dengan portfolio.

## 30.1 Neural Core

Elemen utama untuk merepresentasikan:

**Machine Learning / AI**

Visual:

```text
        ○
     ╱     ╲
   ○   ◉   ○
     ╲     ╱
        ○
```

Komponen:

* Glowing violet nucleus
* Cyan wireframe shell
* Floating neural nodes
* Connecting lines
* Slow rotation
* Subtle pulse
* Small orbital rings

Colors:

```text
Nucleus:
#8b5cf6

Wireframe:
#00f0ff

Neural nodes:
#00ff9d
```

Neural core menjadi **hero 3D centerpiece** apabila sudah tersedia ruang pada design existing.

Jangan mengubah posisi content hero hanya untuk memasukkan object ini.

---

# 31. Cyber Security Shield

Gunakan 3D shield sebagai visual representation untuk:

**Cyber Security / Defensive Security**

Bentuk:

* Geometric shield
* Wireframe structure
* Holographic surface
* Internal glowing core

Visual concept:

```text
        /\
       /  \
      / ◇  \
     /      \
    /________\
```

Material:

```text
Wireframe:
#00ff9d

Core:
#00f0ff

Shadow:
#0a0e17
```

Animation:

* Slow rotation
* Slight vertical floating
* Subtle pulse
* Occasional scanning line

Jangan menggunakan animasi agresif.

---

# 32. 3D Cryptographic Object

Untuk bagian security/PGP, gunakan objek 3D kecil seperti:

* Rotating encrypted cube
* Hexagonal lock
* Key-shaped geometric structure
* Cryptographic sphere

Recommended visual:

```text
        ______
       /_____/|
      |  🔐 | |
      |     | /
      |_____|/
```

Namun icon/key object harus tetap **abstract dan technical**, bukan emoji atau literal cartoon lock.

Material:

```text
Dark metallic surface
+
Cyan emissive edges
+
Subtle green security highlights
```

---

# 33. 3D Web Development Object

Untuk representasi Web Development, gunakan objek 3D geometris:

* Floating browser frame
* Isometric code panel
* Geometric DOM tree
* 3D terminal window
* Floating API nodes

Contoh:

```text
       ┌──────────────┐
      /              /|
     /   CODE       / |
    └──────────────┘  |
    |              | /
    |______________|/
```

Objek harus terasa seperti **technical holographic architecture**.

Jangan membuat browser 3D terlalu besar.

---

# 34. 3D Data / Machine Learning Object

Untuk ML section, gunakan:

### Neural Grid

```text
●────●────●
│ ╲  │  ╱ │
●────●────●
│ ╱  │  ╲ │
●────●────●
```

Representasikan:

* Nodes
* Connections
* Data flow
* Model layers
* Tensor-like structures

Animation:

* Slow node movement
* Data pulses traveling through connections
* Occasional violet signal
* Very subtle rotation

---

# 35. Floating 3D Modules

Tambahkan beberapa **small floating 3D modules** sebagai dekorasi.

Contoh:

```text
[ AI ]
[ WEB ]
[ SEC ]
```

Tetapi jangan hanya berupa text floating.

Bentuk dapat berupa:

* Mini cubes
* Hexagonal modules
* Thin holographic plates
* Small geometric cores

Setiap module memiliki discipline color:

```text
WEB → Cyan
AI  → Violet
SEC → Emerald
```

Movement:

```text
float
+
rotate
+
slight parallax
```

Movement harus sangat lambat.

---

# 36. 3D Data Particles

Background dapat menggunakan procedural particles.

Karakteristik:

* Small
* Sparse
* Low brightness
* Different depth levels
* Slow movement

Particle distribution:

```text
Foreground → very few
Midground   → moderate
Background  → more numerous
```

Jangan membuat particle density terlalu tinggi.

Portfolio content harus tetap menjadi fokus.

---

# 37. Holographic 3D Rings

Gunakan orbital rings untuk elemen penting seperti:

* Neural Core
* Security Shield
* AI model
* System status

Ring dapat memiliki:

```text
rotateX()
rotateY()
rotateZ()
```

dengan kecepatan berbeda.

Contoh:

```text
        ╭────────╮
     ╭──╯   ◉    ╰──╮
        ╰────────╯
```

Ring harus sangat tipis dan glowing.

---

# 38. 3D Geometric Shapes

Gunakan bentuk Three.js native geometry bila memungkinkan:

```text
Icosahedron
Sphere
Torus
Box
Octahedron
Dodecahedron
Cylinder
Cone
```

Prioritaskan geometry procedural.

**Do not add heavy external 3D assets unless absolutely necessary.**

---

# 39. 3D Materials

Material hierarchy:

### Holographic

```text
Transparent
+
Emissive
+
Thin edges
```

### Cyber Metal

```text
Dark surface
+
Metallic highlight
+
Sharp reflection
```

### Neural Energy

```text
Dark base
+
Violet emission
+
Soft bloom
```

### Security Energy

```text
Dark base
+
Emerald emission
+
Cyan edge
```

---

# 40. Depth Layering

Setiap 3D object harus memiliki depth yang jelas.

```text
BACKGROUND
│
├── particles
│
├── ambient glow
│
├── distant geometry
│
├── primary 3D object
│
├── holographic UI
│
└── existing website content
```

3D objects tidak boleh menutupi content.

---

# 41. 3D Interaction

3D elements boleh merespons cursor.

Interaction:

```text
Mouse X
   ↓
rotationY

Mouse Y
   ↓
rotationX
```

Gunakan smooth interpolation.

Recommended:

```text
lerp factor ≈ 0.05
```

Maximum movement:

```text
rotationX ≤ 3°
rotationY ≤ 5°
translation ≤ 10px
```

Jangan menggunakan extreme mouse tracking.

---

# 42. 3D Hover Objects

Untuk object yang berhubungan dengan card:

```text
Idle
 ↓
Object floating
 ↓
Hover
 ↓
Object moves slightly forward
 ↓
Edge glow increases
 ↓
Return smoothly
```

Contoh:

```text
translateZ(8px)
scale(1.015)
```

Jangan menggunakan:

```text
scale(1.2)
rotate(45deg)
```

---

# 43. 3D Object Placement

**Placement harus mengikuti existing design.**

Prioritas:

```text
1. Existing empty space
2. Background layer
3. Decorative side area
4. Existing visual container
5. Never cover important content
```

Jika tidak tersedia ruang kosong:

> **Do not force the 3D object into the layout.**

Lebih baik memiliki sedikit elemen 3D yang bagus daripada memenuhi halaman dengan objek.

---

# 44. 3D Element Density

Target density:

### Hero

1 major 3D object
+
2–5 minor decorative objects

### Section

0–1 major 3D object
+
small ambient elements

### Project Cards

Mostly 3D **depth**, bukan full 3D objects.

### Security Section

1 security-related 3D object

### Footer

Minimal / none.

---

# 45. Three.js Architecture

Jika project sudah menggunakan Three.js:

**REUSE existing architecture.**

Jangan membuat:

```text
Renderer #1
Renderer #2
Renderer #3
Renderer #4
```

Gunakan:

```text
One Renderer
      ↓
One Scene
      ↓
Multiple Groups
      ↓
Multiple 3D Objects
```

Contoh structure:

```text
Scene
│
├── BackgroundParticles
├── NeuralCore
├── SecurityShield
├── CryptoObject
├── FloatingModules
└── AmbientGeometry
```

---

# 46. 3D Performance Rules

Prioritaskan performance.

Gunakan:

* Low-poly geometry
* InstancedMesh untuk banyak particle
* Shared materials
* Shared geometries
* Reusable render loop
* Device pixel ratio limit
* Frustum culling
* Reduced effects on mobile

Target:

```text
Desktop:
smooth 60 FPS target

Mobile:
stable and lightweight
```

Jika device tidak mampu menjalankan full 3D:

```text
Full 3D
   ↓
Reduced 3D
   ↓
Static visual
```

Website tetap harus berfungsi normal.

---

# 47. Mobile 3D

Mobile tidak membutuhkan seluruh desktop 3D.

Gunakan:

```text
Desktop:
Full 3D + parallax

Tablet:
Reduced 3D

Mobile:
Simplified 3D
```

Mobile boleh:

* Mengurangi particles
* Mengurangi animation
* Mengurangi shadow
* Mengurangi object count
* Disable mouse parallax

Tetapi **jangan menghapus visual identity utama.**

---

# 48. Visual Hierarchy

3D tidak boleh mengalahkan typography.

Priority:

```text
CONTENT
  ↓
UI
  ↓
3D OBJECT
  ↓
DECORATION
```

Bukan:

```text
3D OBJECT
  ↓
GLOW
  ↓
PARTICLES
  ↓
CONTENT
```

Jika user melihat portfolio, mereka harus membaca:

1. Who I am
2. What I do
3. Skills
4. Projects
5. Security/technical capabilities
6. Contact

3D hanya memperkuat storytelling.

---

# 49. Semantic 3D

Setiap object 3D harus mempunyai alasan.

### Neural Core

AI / Machine Learning

### Shield

Cyber Security

### Code Architecture

Web Development

### Crypto Object

Security / PGP

### Data Network

Machine Learning / Data

### Orbital Ring

System / Encryption / Neural computation

**Jangan menambahkan 3D object hanya karena terlihat keren.**

---

# 50. Final 3D Quality Standard

Final website harus memberikan kesan:

> **"This is the same Cyber Command portfolio, but it feels like a physical futuristic command system."**

Bukan:

> "This is a completely different 3D website."

### Absolute Rules

**PRESERVE:**

* Existing layout
* Existing content
* Existing typography
* Existing colors
* Existing components
* Existing functionality
* Existing navigation
* Existing responsive behavior

**ENHANCE:**

* 3D depth
* 3D objects
* Spatial hierarchy
* Lighting
* Shadows
* Perspective
* Material
* Neural effects
* Holographic elements
* Controlled animation
* Micro-interactions

**DO NOT:**

* Redesign
* Replace
* Remove
* Reorganize
* Over-animate
* Over-glow
* Overload the page
* Sacrifice performance
* Sacrifice readability

> **The objective is not to make the website "more 3D".**
>
> **The objective is to make the existing Cyber Command interface feel physically dimensional, intelligent, and technologically advanced.**

# 51. Example 3D Component Implementations

> These examples are **implementation references**, not instructions to replace the existing UI.
>
> AI agent harus menyesuaikan implementasi dengan architecture dan component structure yang sudah ada.

---

## 51.1 Neural Core — Three.js

Neural Core adalah contoh utama elemen 3D untuk bagian AI/ML.

### Visual Structure

```text
                 ○
             ╱       ╲
          ○             ○
           ╲    ◉    ╱
          ○ ────┼──── ○
           ╲         ╱
             ○─────○

       Rotating Neural Core
```

### Three.js Example

```js
const group = new THREE.Group();

const coreGeometry = new THREE.IcosahedronGeometry(1.25, 1);

const coreMaterial = new THREE.MeshBasicMaterial({
    color: 0x00f0ff,
    wireframe: true,
    transparent: true,
    opacity: 0.7
});

const core = new THREE.Mesh(
    coreGeometry,
    coreMaterial
);

group.add(core);
```

### AI Nucleus

```js
const nucleusGeometry = new THREE.SphereGeometry(0.45, 32, 32);

const nucleusMaterial = new THREE.MeshBasicMaterial({
    color: 0x8b5cf6,
    transparent: true,
    opacity: 0.9
});

const nucleus = new THREE.Mesh(
    nucleusGeometry,
    nucleusMaterial
);

group.add(nucleus);
```

### Animation

```js
function animateNeuralCore(time) {
    core.rotation.x += 0.002;
    core.rotation.y += 0.004;

    const pulse =
        1 + Math.sin(time * 0.002) * 0.06;

    nucleus.scale.setScalar(pulse);
}
```

**Important:** Jika project sudah memiliki animation loop, masukkan logic ini ke loop existing. Jangan membuat animation loop baru.

---

# 51.2 Orbital Encryption Rings

Gunakan Torus sebagai representasi encryption / system orbit.

```js
const ringGeometry = new THREE.TorusGeometry(
    1.7,
    0.018,
    12,
    96
);

const ringMaterial = new THREE.MeshBasicMaterial({
    color: 0x00f0ff,
    transparent: true,
    opacity: 0.45
});

const ring = new THREE.Mesh(
    ringGeometry,
    ringMaterial
);

ring.rotation.x = Math.PI / 2.5;

group.add(ring);
```

Animation:

```js
ring.rotation.z += 0.003;
ring.rotation.x += 0.0005;
```

Tambahkan 2–3 ring dengan ukuran dan rotation berbeda.

Jangan membuat terlalu banyak ring.

---

# 51.3 Neural Nodes

Representasikan hubungan antar-neuron dengan small spheres.

```js
const nodeGeometry =
    new THREE.SphereGeometry(0.035, 8, 8);

const nodeMaterial =
    new THREE.MeshBasicMaterial({
        color: 0x00ff9d
    });

const nodes = [];

for (let i = 0; i < 55; i++) {
    const node = new THREE.Mesh(
        nodeGeometry,
        nodeMaterial
    );

    node.position.set(
        (Math.random() - 0.5) * 4,
        (Math.random() - 0.5) * 4,
        (Math.random() - 0.5) * 4
    );

    nodes.push(node);
    group.add(node);
}
```

Node movement harus sangat kecil:

```js
node.position.y +=
    Math.sin(time * 0.001 + index) * 0.0005;
```

Tujuannya membuat network terasa hidup tanpa terlihat chaotic.

---

# 51.4 Synaptic Connections

Hubungkan node menggunakan `LineSegments`.

```js
const lineMaterial = new THREE.LineBasicMaterial({
    color: 0x00f0ff,
    transparent: true,
    opacity: 0.18
});
```

Connections harus:

* Thin
* Low opacity
* Sparse
* Procedural

Jangan menghubungkan semua node dengan semua node.

Target visual:

```text
●────●
│ ╲  │
│  ╲ │
●────●────●
     ╲
      ●
```

---

# 51.5 Floating Cyber Cube

Gunakan cube kecil sebagai decorative 3D element.

```js
const geometry =
    new THREE.BoxGeometry(0.45, 0.45, 0.45);

const material =
    new THREE.MeshBasicMaterial({
        color: 0x00f0ff,
        wireframe: true,
        transparent: true,
        opacity: 0.55
    });

const cube =
    new THREE.Mesh(geometry, material);

cube.position.set(
    2.2,
    0.8,
    -0.5
);
```

Animation:

```js
cube.rotation.x += 0.004;
cube.rotation.y += 0.006;

cube.position.y =
    baseY + Math.sin(time * 0.001) * 0.08;
```

Cube hanya sebagai dekorasi.

Jangan sampai menutupi CTA atau text.

---

# 51.6 3D Security Shield

Gunakan `ShapeGeometry` atau `ExtrudeGeometry` untuk membuat shield procedural.

Concept:

```text
          /\
         /  \
        /    \
       /      \
      /        \
      \        /
       \      /
        \____/
```

Contoh:

```js
const shape = new THREE.Shape();

shape.moveTo(0, 1.2);
shape.lineTo(0.8, 0.7);
shape.lineTo(0.7, -0.4);
shape.lineTo(0, -1.1);
shape.lineTo(-0.7, -0.4);
shape.lineTo(-0.8, 0.7);
shape.closePath();

const geometry = new THREE.ExtrudeGeometry(
    shape,
    {
        depth: 0.12,
        bevelEnabled: true,
        bevelThickness: 0.02,
        bevelSize: 0.02,
        bevelSegments: 2
    }
);
```

Material:

```js
const material =
    new THREE.MeshBasicMaterial({
        color: 0x00ff9d,
        wireframe: true,
        transparent: true,
        opacity: 0.6
    });
```

Gunakan shield sebagai visual security identity.

---

# 51.7 Holographic Data Panel

Untuk element yang terlihat seperti floating HUD:

```text
┌─────────────────────────┐
│ SYSTEM TELEMETRY        │
│                         │
│ CPU      42%            │
│ MEMORY   61%            │
│ STATUS   SECURE         │
└─────────────────────────┘
```

Panel dapat tetap dibuat menggunakan HTML/CSS.

3D hanya digunakan pada:

* `translateZ`
* perspective
* floating movement
* shadow
* glow

**Tidak perlu membuat seluruh HUD menggunakan WebGL.**

Recommended architecture:

```text
Three.js
   ↓
3D background/object

HTML/CSS
   ↓
Readable UI
```

Ini lebih accessible dan lebih mudah responsive.

---

# 51.8 3D Project Object

Project card tetap HTML/CSS.

Tambahkan optional 3D visual di area visual project.

Contoh:

```text
┌──────────────────────────────┐
│                              │
│       ╭──────────╮           │
│      ╱  PROJECT   ╲          │
│     ╱   SYSTEM     ╲         │
│     ╲              ╱         │
│      ╲────────────╱          │
│                              │
│  Django · Python · ML        │
└──────────────────────────────┘
```

3D object dapat berupa:

* Mini server
* Neural grid
* Database cylinder
* API nodes
* Browser frame

Object harus menjadi visual representation dari project.

---

# 51.9 3D Server Stack

Untuk project backend / infrastructure:

```js
const serverGeometry =
    new THREE.BoxGeometry(
        0.8,
        1.6,
        0.45
    );

const serverMaterial =
    new THREE.MeshStandardMaterial({
        color: 0x181b25,
        metalness: 0.75,
        roughness: 0.3
    });

const server =
    new THREE.Mesh(
        serverGeometry,
        serverMaterial
    );
```

Tambahkan beberapa small emissive LEDs:

```js
const ledGeometry =
    new THREE.SphereGeometry(
        0.025,
        8,
        8
    );

const ledMaterial =
    new THREE.MeshBasicMaterial({
        color: 0x00ff9d
    });
```

Hasil visual:

```text
┌───────────┐
│ ●         │
│ ●         │
│ ●         │
│ ●         │
└───────────┘
```

Cocok untuk:

* Backend
* API
* Database
* DevOps
* Security infrastructure

---

# 51.10 3D Database Cylinder

Untuk project database:

```js
const geometry =
    new THREE.CylinderGeometry(
        0.6,
        0.6,
        0.8,
        32
    );

const material =
    new THREE.MeshStandardMaterial({
        color: 0x181b25,
        metalness: 0.7,
        roughness: 0.35
    });

const database =
    new THREE.Mesh(
        geometry,
        material
    );
```

Tambahkan cyan/emerald edge highlight.

Database dapat berputar sangat lambat:

```js
database.rotation.y += 0.0015;
```

---

# 51.11 3D Code Architecture

Untuk Web Development section:

```text
        [ FRONTEND ]
             │
             ▼
        [ API LAYER ]
             │
             ▼
        [ BACKEND ]
             │
             ▼
        [ DATABASE ]
```

Representasikan menggunakan nodes + connecting lines.

Contoh hierarchy:

```js
const architecture = new THREE.Group();

architecture.add(frontendNode);
architecture.add(apiNode);
architecture.add(backendNode);
architecture.add(databaseNode);
```

Connections menggunakan `LineSegments`.

Animation dapat menunjukkan data packet bergerak dari:

```text
Frontend
   ↓
API
   ↓
Backend
   ↓
Database
```

Gunakan sangat subtle.

---

# 51.12 3D AI Model Layers

Representasikan neural network sebagai beberapa layer:

```text
Input
 ● ● ●
  ╲│╱
 ● ● ● ●
  ╲│╱
  ● ●
Output
```

Layer dapat menggunakan:

* Sphere nodes
* Thin connecting lines
* Violet emissive accents

Contoh:

```js
const layers = [
    5,
    7,
    4,
    2
];
```

Jangan membuat network terlalu kompleks.

Visual simplicity lebih penting.

---

# 51.13 Holographic Ring Around UI

Untuk existing component yang membutuhkan visual focus:

```css
.component {
    position: relative;
    transform-style: preserve-3d;
}
```

Tambahkan decorative ring:

```css
.component::before {
    content: "";
    position: absolute;
    inset: -8px;
    border: 1px solid rgba(0, 240, 255, 0.12);
    border-radius: inherit;
    transform: translateZ(-4px);
    pointer-events: none;
}
```

Ring hanya sebagai depth layer.

---

# 51.14 CSS 3D Card Tilt

Jika existing cards cocok dengan hover tilt:

```js
function updateTilt(element, x, y) {
    const rect = element.getBoundingClientRect();

    const px =
        (x - rect.left) / rect.width;

    const py =
        (y - rect.top) / rect.height;

    const rotateY =
        (px - 0.5) * 4;

    const rotateX =
        (0.5 - py) * 3;

    element.style.transform =
        `perspective(1000px)
         rotateX(${rotateX}deg)
         rotateY(${rotateY}deg)
         translateZ(4px)`;
}
```

Maximum:

```text
rotateX: ±3°
rotateY: ±4°
translateZ: 4px
```

Jangan melebihi nilai tersebut tanpa alasan visual yang kuat.

---

# 51.15 3D Hover Lighting

Tambahkan light position berdasarkan cursor.

Concept:

```text
Cursor
   ↓
┌──────────────┐
│ ↘ light      │
│              │
│      CARD    │
│              │
└──────────────┘
```

Implementasi dapat menggunakan CSS custom properties:

```js
element.style.setProperty(
    "--mouse-x",
    `${x * 100}%`
);

element.style.setProperty(
    "--mouse-y",
    `${y * 100}%`
);
```

CSS:

```css
.card::before {
    background:
        radial-gradient(
            circle at var(--mouse-x) var(--mouse-y),
            rgba(0, 240, 255, 0.12),
            transparent 35%
        );
}
```

Ini memberikan kesan permukaan 3D tanpa WebGL tambahan.

---

# 51.16 3D Data Pulse

Untuk menunjukkan data transmission, gunakan small glowing sphere.

```js
const packet =
    new THREE.Mesh(
        new THREE.SphereGeometry(
            0.025,
            8,
            8
        ),
        new THREE.MeshBasicMaterial({
            color: 0x00f0ff
        })
    );
```

Packet bergerak sepanjang path:

```text
●──────────────●
       → ●
```

Gunakan linear interpolation:

```js
packet.position.lerpVectors(
    start,
    end,
    progress
);
```

Progress harus berjalan lambat.

---

# 51.17 3D Scan Effect

Security objects dapat memiliki scanning animation.

Concept:

```text
██████████████
       ↓
      SCAN
       ↓
██████████████
```

Implementasi:

```text
Thin horizontal plane
+
Emerald/Cyan emissive material
+
Slow vertical movement
```

Scan effect hanya berjalan sesekali.

Jangan melakukan infinite aggressive scanning pada semua component.

---

# 51.18 3D Grounding Shadow

Agar floating object benar-benar terlihat berada di ruang 3D, tambahkan shadow/ambient ellipse di bawah object.

Concept:

```text
       ◉
      /|\
       |
       |
    ───────
    shadow
```

CSS alternative:

```css
.object-shadow {
    width: 60%;
    height: 12px;
    border-radius: 50%;
    background: rgba(0, 0, 0, 0.45);
    filter: blur(10px);
    transform: translateZ(-10px);
}
```

Shadow harus subtle.

---

# 51.19 Combining 3D + Existing UI

Recommended architecture:

```text
PAGE
│
├── Existing Navigation
│
├── Hero
│   ├── Existing Text
│   ├── Existing CTA
│   └── 3D Neural Core
│
├── Existing Skills
│   └── Small 3D decorative elements
│
├── Existing Projects
│   └── Existing Cards
│       └── Optional 3D visual
│
├── Security
│   ├── Existing PGP component
│   └── 3D Security Shield
│
└── Existing Footer
```

3D layer harus **coexist**, bukan menggantikan UI.

---

# 52. Suggested 3D Component Map

Gunakan semantic mapping berikut:

| Area           | 3D Element         | Primary Color    |
| -------------- | ------------------ | ---------------- |
| Hero           | Neural Core        | Cyan + Violet    |
| AI / ML        | Neural Network     | Violet           |
| Web Dev        | Architecture Nodes | Cyan             |
| Backend        | Server Stack       | Cyan             |
| Database       | Database Cylinder  | Cyan             |
| Cyber Security | Security Shield    | Emerald          |
| PGP            | Crypto Orb / Ring  | Emerald + Cyan   |
| System Status  | Holographic Ring   | Emerald          |
| Background     | Data Particles     | Cyan/Violet      |
| Decorative     | Floating Geometry  | Discipline-based |

---

# 53. 3D Implementation Rules for AI Agent

Sebelum membuat object baru:

```text
1. Check existing component.
2. Check existing layout.
3. Check existing Three.js scene.
4. Reuse existing renderer.
5. Reuse existing animation loop.
6. Add object as a child/group.
7. Keep object behind important UI.
8. Test desktop.
9. Test mobile.
10. Test reduced-motion.
```

### Never:

```text
Create a new page
Create a new layout
Replace existing UI
Remove existing functionality
Create multiple unnecessary WebGL canvases
Add heavy 3D assets
Add excessive post-processing
```

---

# 54. Final 3D Implementation Philosophy

The implementation should feel like:

```text
Existing Website
       +
Real 3D Objects
       +
Procedural Geometry
       +
Holographic UI
       +
Spatial Lighting
       +
Controlled Motion
       ↓
Cyber Command
```

Bukan:

```text
3D Demo
    +
Random UI
    +
Random Effects
```

### Final Rule

> **3D must support the story of the portfolio.**
>
> Web Development → architecture and data flow.
>
> Machine Learning → neural networks and computational cores.
>
> Cyber Security → shields, encryption, secure nodes.
>
> Backend → servers and infrastructure.
>
> Database → data storage structures.
>
> System → telemetry and command objects.
>
> Every 3D object must have a semantic purpose while preserving the existing design and functionality.
