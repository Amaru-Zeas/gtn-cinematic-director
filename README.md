# Cinema Setup Widget Library

A sleek, scroll-wheel cinematography widget for Griptape Nodes with built-in LLM prompt generation.

## What It Does

**Scroll. Select. Generate.** Mouse-wheel through six categories of cinema equipment, then let a built-in AI agent craft a professional cinematic prompt from your setup.

## The Widget

Six columns, each scrollable with mouse wheel:

| Column | Options | Examples |
|--------|---------|----------|
| **Camera** | 10 bodies | Full-Frame Cine, ARRI ALEXA 65, RED V-RAPTOR, IMAX 65mm |
| **Lens** | 10 types | Spherical, Anamorphic, Vintage, Tilt-Shift, Petzval |
| **Focal Length** | 12 lengths | 14mm ultra-wide to 300mm telephoto |
| **Aperture** | 11 stops | f/1.2 ultra-shallow to f/22 deep focus |
| **Lighting** | 12 styles | Golden Hour, Neon Noir, Chiaroscuro, Volumetric Fog |
| **Film Stock** | 11 stocks | Kodak Portra, CineStill 800T, Fuji Velvia, Ilford HP5 |

## Features

- **Mouse wheel scrolling** on each column to browse options
- **Arrow buttons** for precise navigation
- **Save setups** — bookmark favorite combinations
- **Load saved setups** — click a saved chip to restore
- **Built-in LLM agent** — generates detailed cinematic prompts
- **Streaming output** — watch the prompt build in real-time
- **Optional subject input** — guide the scene direction
- **Setup summary** — human-readable equipment list

## Node: Cinema Prompt Generator

### Inputs
- **cinema_setup** (widget) — The scroll-wheel selector
- **subject** (text) — Optional scene/subject hint

### Outputs
- **prompt_output** — The generated cinematic prompt (feed to image generators)
- **setup_summary** — Human-readable equipment summary
- **setup_json** — Raw JSON for downstream processing

## Requirements

- OpenAI API key (for prompt generation)
- Griptape Nodes engine
