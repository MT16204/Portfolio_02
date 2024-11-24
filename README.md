# Portfolio website

This my second portfolio, built with HTML, CSS, JavaScript, and enhanced with WebGL and GLSL to showcase interactive and dynamic 2D and 3D graphics.
https://mt16204.github.io/Portfolio_02/index.html

# Screenshot
<img width="1263" alt="Screen Shot 2024-11-24 at 14 16 34" src="https://github.com/user-attachments/assets/114755ca-97ee-485f-8037-17c16085d6b7">

# Technologies Used
- **HTML**: Structure and layout of the portfolio page.
- **CSS**: Styling and animation of elements.
- **JavaScript**: Logic for dynamic content and user interactions.
- **WebGL**: Core technology for rendering 2D and 3D graphics directly in the browser, utilizing the GPU for high-performance rendering.
- **GLSL (OpenGL Shading Language)**: Used to write custom shaders for effects like noise, UV mapping, and color conversions.

# Key Techniques & Effects

### 1. **Vertex Shader and Fragment Shader**
   - **Vertex Shader**: Calculates the position of each vertex in 3D space and transforms it accordingly.
   - **Fragment Shader**: Calculates the color of each pixel, applying textures, lighting, and color effects.

### 2. **Simplex Noise**
   - Used to generate smooth random noise patterns that add organic movement and texture effects to the graphics.

### 3. **UV Mapping**
   - Adjusts texture coordinates (UV) for accurate mapping of 2D textures to 3D surfaces, ensuring a seamless and realistic look.

### 4. **HSB to RGB Conversion**
   - Allows for more flexible and vibrant color manipulation by converting HSB (Hue, Saturation, Brightness) values to RGB (Red, Green, Blue) for rendering on the screen.
