# ComfyUI Worlds Workflows

This repository contains a curated collection of ComfyUI workflows for generating, editing, and extending 3D scenes (or “worlds”), as well as creating 360-degree and panoramic imagery. The workflows are provided as `.json` files and can be imported directly into a ComfyUI environment, allowing users to experiment with immersive image generation, panoramic scene creation, and image-to-3D conversion for creative, technical, and research-oriented applications.

The repository is organised into three main folders:

- `workflows/`  
  Contains the ComfyUI workflow files in `.json` format. These files can be loaded directly into ComfyUI and used as ready-made pipelines for immersive image generation, panoramic transformation, and 3D asset creation.

- `ComfyUI screenshots/`  
  Contains screenshots of each workflow as displayed in the ComfyUI interface. These images provide a quick visual reference for the node structure, workflow logic, and overall layout of each pipeline.

- `examples/`  
  Contains example outputs generated using the workflows. These examples illustrate the intended use cases and visual capabilities of each workflow.

## Workflows

### Flux Kontext 360 Degree LoRA

The Flux Kontext 360 Degree LoRA workflow is designed to generate seamless 360-degree-style images with improved depth, perspective coherence, and visual consistency. It is particularly useful for creating immersive panoramic scenes, virtual reality environments, spherical backgrounds, and experimental visual worlds from standard images or prompts. The workflow is well suited to VR content creation, immersive media, panoramic photography, and digital storytelling. Its main strength lies in producing wraparound imagery where the edges connect naturally, helping users create believable and visually continuous 360-degree outputs.



https://github.com/user-attachments/assets/5d122f4c-478e-4d6f-a661-0651be3e5c72



https://github.com/user-attachments/assets/3cc12eb4-e057-4a4c-9b7c-2a76414aef77



https://github.com/user-attachments/assets/afb74302-de08-4805-914a-25f420985424



### Image to 3D Object

The Image to 3D Object workflow converts a single frontal image into a detailed and consistent 3D model. It uses AI-based multi-angle reconstruction and 3D generation techniques to infer the geometry and missing views of the subject, making it valuable for rapid asset creation from minimal source material. This workflow is especially useful for gaming, storytelling, virtual worlds, interactive media, and digital content production where fast 3D prototyping is required. It provides an accessible pipeline for transforming a 2D visual input into a reusable 3D object within a ComfyUI-based workflow.

<img width="1088" height="1088" alt="lucky_cat_sculpture_front" src="https://github.com/user-attachments/assets/46f35430-f16b-4e28-95db-b6d144acfe9a" />

<img width="1370" height="830" alt="Untitled" src="https://github.com/user-attachments/assets/b38e60ae-164c-46e2-af8e-22d063b77d8b" />


### Panoramic (360) Image from a Single Image

This workflow generates a panoramic image from a single uploaded image, extending the original scene into a wider immersive composition. It is particularly suitable for the creation of 360-style visual content, panoramic photography experiments, immersive environments, and VR-related scene development. The workflow offers a practical way to transform standard images into broader spatial experiences without manually constructing the surrounding context. It is therefore useful for users exploring virtual tours, immersive visualisation, and atmospheric scene generation.

<img width="2075" height="1024" alt="panoramic-image-gemini-chatgpt-comp" src="https://github.com/user-attachments/assets/fbe57571-8c62-42bc-bc39-12ca9f2067e1" />


## How to Use

1. Open ComfyUI.
2. Drag and drop a `.json` file from the `workflows/` folder into the ComfyUI canvas, or load it through the ComfyUI interface.
3. Check that all required models, custom nodes, and dependencies are installed in your local ComfyUI environment.
4. Add or replace the input images and prompts where required.
5. Queue the workflow and review the generated output.
6. Compare your results with the files in the `examples/` folder where relevant.

## Notes

Some workflows may require specific models, custom nodes, or hardware resources to run successfully. If a workflow does not execute immediately, check the missing-node or missing-model messages in ComfyUI and install the necessary components before retrying.

The workflows in this repository are intended as practical starting points. Users are encouraged to adapt prompts, model settings, control parameters, and node structures according to their own creative, technical, or research requirements.

## Acknowledgements

The workflows in this repository are based on publicly available ComfyUI workflow examples and model ecosystems, including workflows documented by RunComfy and Comfy.org. Please consult the relevant workflow pages, model documentation, and licensing terms for each workflow and associated model before using them in production, commercial, or research contexts.

## Repository Structure

```text
ComfyUI-wrld-workflows/
│
├── workflows/
│   ├── Flux Kontext 360 Degree LoRA.json
│   ├── Image to 3D Object.json
│   └── Panoramic (360) Image from a Single Image.json
│
├── ComfyUI screenshots/
│   └── Screenshots of each workflow in ComfyUI
│
└── examples/
    └── Example outputs generated using the workflows
