````markdown
# Mockup Generator Prompts

A professional collection of highly detailed prompts for generating realistic product mockups from your own logos, designs, UI screens, and brand assets.

Place your design on **T-shirts, mugs, tote bags, packaging, billboards, smartphones, complete branded environments, and advertising campaigns** with realistic materials, lighting, perspective, shadows, reflections, and commercial photography.

The prompts are designed to work as reusable templates with customizable `[VARIABLES]`.

## Contents

| Prompt | Description |
|---|---|
| [`01-tshirt.md`](01-camiseta.md) | Realistic T-shirt and apparel mockup |
| [`02-cup.md`](02-taza.md) | Ceramic mug product photography |
| [`03-tote-bag.md`](03-tote-bag.md) | Premium tote bag lifestyle mockup |
| [`04-packaging-box.md`](04-packaging-box.md) | Branded packaging and product box |
| [`05-billboard.md`](05-billboard.md) | Large-scale outdoor billboard advertising |
| [`06-smartphone.md`](06-smartphone.md) | Smartphone and digital interface mockup |
| [`07-full-branding-scene.md`](07-full-branding-scene.md) | Complete multi-product branding environment |
| [`08-master-campaign.md`](08-master-campaign.md) | Premium commercial campaign combining multiple mockups |

## Features

These prompts are designed with a strong focus on visual realism and production quality.

- Photorealistic commercial imagery
- Accurate product proportions
- Realistic materials and surface textures
- Physically plausible fabric deformation
- Natural folds, wrinkles, seams, and stitching
- Realistic reflections and refractions
- Accurate shadows and contact shadows
- Natural environmental lighting
- Professional studio and advertising photography
- Realistic camera perspective and depth of field
- High-quality product presentation
- Consistent brand identity
- Precise logo and artwork placement
- Preservation of the original uploaded design
- Customizable scenes and environments
- Configurable camera angles and compositions
- Dedicated negative-prompt sections
- Reusable `[VARIABLE]` system

## Basic Usage

Each prompt contains variables enclosed in square brackets.

For example:

```text
[REFERENCE_ASSET]
[BRAND_NAME]
[PRODUCT_TYPE]
[PRODUCT_COLOR]
[PRINT_POSITION]
[PRINT_METHOD]
[LIGHTING]
[CAMERA]
[ANGLE]
[BACKGROUND]
[OUTPUT_RATIO]
[NEGATIVE_PROMPT]
````

Replace the variables with your desired values before submitting the prompt to your image-generation model.

Example:

```text
[REFERENCE_ASSET] = uploaded Azure logo
[BRAND_NAME] = Azure
[PRODUCT_TYPE] = oversized black T-shirt
[PRODUCT_COLOR] = matte black
[PRINT_POSITION] = centered on the chest
[PRINT_METHOD] = high-quality screen print
[LIGHTING] = soft commercial studio lighting
[CAMERA] = 85mm professional product photography lens
[ANGLE] = front three-quarter view
[BACKGROUND] = minimal dark gray studio
[OUTPUT_RATIO] = 4:5
```

## Reference Assets

The prompts are intended to work with uploaded reference assets such as:

- Logos
- Brand marks
- Illustrations
- Product designs
- UI screenshots
- Typography
- Packaging artwork
- Posters
- Advertising graphics
- App interfaces
- Complete visual identities

When a reference asset is provided, the prompt explicitly instructs the image model to preserve the original artwork rather than redesigning or recreating it.

The reference should remain visually consistent in:

- Shape
- Typography
- Colors
- Proportions
- Composition
- Symbol placement
- Graphic details

## Customization

### Product

Modify the product-related variables to generate different physical objects.

Examples:

```text
[PRODUCT_TYPE] = heavyweight cotton T-shirt
[PRODUCT_TYPE] = ceramic coffee mug
[PRODUCT_TYPE] = canvas tote bag
[PRODUCT_TYPE] = premium cardboard box
[PRODUCT_TYPE] = city-center billboard
[PRODUCT_TYPE] = modern flagship smartphone
```

### Environment

The environment can be completely customized.

Examples:

```text
[BACKGROUND] = minimal white studio
[BACKGROUND] = modern concrete architecture
[BACKGROUND] = premium retail store
[BACKGROUND] = urban street at night
[BACKGROUND] = luxury office
[BACKGROUND] = futuristic technology showroom
```

### Lighting

Examples:

```text
[LIGHTING] = soft diffused studio lighting
[LIGHTING] = dramatic cinematic lighting
[LIGHTING] = warm golden-hour sunlight
[LIGHTING] = overcast natural daylight
[LIGHTING] = high-end commercial product lighting
```

### Photography

The prompts support detailed camera configuration.

Examples:

```text
[CAMERA] = 85mm portrait lens
[CAMERA] = 50mm commercial photography lens
[CAMERA] = wide-angle architectural lens
[CAMERA] = macro product photography lens
```

You can also customize:

```text
[ANGLE]
[FOCUS]
[DEPTH_OF_FIELD]
[CAMERA_HEIGHT]
[FRAMING]
[OUTPUT_RATIO]
```

## Realism Requirements

The prompts prioritize physical realism rather than simply placing a flat image over an object.

For example, artwork printed on fabric should naturally follow:

- Fabric folds
- Surface curvature
- Stretching
- Wrinkles
- Perspective
- Material texture
- Lighting conditions

Similarly, artwork placed on packaging should respect:

- Box geometry
- Edges
- Corners
- Paper texture
- Printing imperfections
- Surface reflections
- Perspective distortion

The goal is to make the final result appear as if the branded object actually exists and was photographed professionally.

## Negative Prompts

Every prompt includes a dedicated `[NEGATIVE_PROMPT]` section.

This can be customized depending on the image model being used.

Typical exclusions include:

```text
distorted logo,
incorrect typography,
misspelled text,
extra letters,
duplicated objects,
warped geometry,
incorrect proportions,
floating objects,
unrealistic shadows,
plastic-looking materials,
low-resolution textures,
artificial reflections,
excessive blur,
oversaturated colors,
deformed products,
cropped objects,
unwanted people,
watermarks,
random text,
AI artifacts
```

## Example

A simple configuration could look like:

```text
[REFERENCE_ASSET] = uploaded brand logo
[BRAND_NAME] = Azure
[PRODUCT_TYPE] = premium oversized white T-shirt
[SHIRT_COLOR] = white
[PRINT_POSITION] = centered chest
[PRINT_METHOD] = high-quality screen printing
[LIGHTING] = soft directional studio lighting
[CAMERA] = 85mm commercial photography lens
[ANGLE] = front three-quarter angle
[BACKGROUND] = minimalist premium studio
[OUTPUT_RATIO] = 4:5
```

The corresponding prompt can then be used to generate a professional commercial mockup while maintaining the identity of the original design.

## Repository Structure

```text
mockup-generator-prompts/
│
├── 01-camiseta.md
├── 02-taza.md
├── 03-tote-bag.md
├── 04-packaging-box.md
├── 05-billboard.md
├── 06-smartphone.md
├── 07-full-branding-scene.md
├── 08-master-campaign.md
└── README.md
```

## Intended Use

This repository is intended for:

- Brand visualization
- Product presentations
- Design previews
- Marketing campaigns
- Social media content
- Portfolio presentations
- E-commerce concepts
- Startup branding
- UI/product showcases
- Advertising concepts
- Creative direction
- Client presentations

It can also be used to quickly test how an existing visual identity would look across different physical and digital environments.

## Prompt Philosophy

The prompts are designed around four main principles:

### 1. Preserve the Design

The uploaded artwork should remain faithful to the original reference.

### 2. Respect the Physical World

Products should behave like real physical objects, including their materials, geometry, lighting, and imperfections.

### 3. Control the Photography

Camera position, lens characteristics, depth of field, lighting, framing, and composition should be explicitly controlled.

### 4. Produce Commercial-Quality Results

The final image should resemble professional advertising, product photography, or a high-end brand campaign rather than a generic AI-generated image.

## Future Extensions

Additional prompt categories can be added over time, including:

- Clothing collections
- Shoes
- Caps
- Posters
- Storefronts
- Vehicles
- Product labels
- Bottles and cans
- Websites
- Tablets
- Laptops
- Gaming setups
- Event banners
- Restaurant branding
- Retail interiors
- Social media advertisements
- Magazine advertisements
- Packaging collections
- Corporate environments

## Contributing

Contributions are welcome.

When adding a new prompt:

1. Keep the prompt highly detailed and reusable.
2. Use `[VARIABLE]` placeholders for customizable parameters.
3. Include realistic material and lighting instructions.
4. Include camera and composition specifications.
5. Include a comprehensive negative prompt.
6. Avoid unnecessary model-specific assumptions.
7. Keep the prompt compatible with general image-generation workflows.
8. Preserve the existing repository structure and naming convention.

## License

The prompts in this repository can be distributed under the license specified by the repository owner.

Generated images are separate from the prompt files and may be subject to the terms, conditions, and usage policies of the image-generation platform or model used to create them.

## Goal

The goal of this project is to provide a reusable library of professional-grade prompts for transforming existing designs into convincing real-world mockups.

Instead of manually describing every aspect of a scene, you can configure a small set of variables and generate a consistent visual presentation across multiple products, environments, and advertising formats.