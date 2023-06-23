# ACG-Platanos
La generación de imagenes puede servir para entrenar modelos más pequeños y más especificos, además, por lo visto se esta utilizando torch y no solo tensorflow para la generación de imagenes, por lo tanto para el proyecto de algoritmos de computación grafica se esta usando el modelo `majicMixRealistic`.safetensors para la generación de imagenes precisas de platanos de seda, con ciertas caracteristicas que buscamos en platanos de `excelente calidad`, `calidad regular`, `calidad baja` y `mala calidad` para asi poder clasificarlos y generar un `modelo de reconocimiento de plátanos` preciso que nos diga la calidad de los plátanos.

Darle clic al botón de play:

![](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.001.png)

Dale clic al enlace generado, el que termina con gradio.live

![Texto

Descripción generada automáticamente](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.002.png)

Generar 500 imágenes de golpe (tiempo estimado 30min~50min): 

![Imagen de la pantalla de un celular con letras

Descripción generada automáticamente con confianza media](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.003.png)

Tamaño 512px de alto y 512px ancho

![Patrón de fondo

Descripción generada automáticamente](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.004.png)

Números de pasos que tendrá la imagen, aceptable entre [20~35]

![](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.005.png)

Tendrán acceso a 2 modelos, [CyberRealistic](https://civitai.com/models/15003/cyberrealistic) (genera todo tipo de imágenes) y otro [FruitFusion](https://civitai.com/models/18742/fruit-fusion) (mezcla frutas y también las genera sin mezclar): 

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.006.png)

Existen 2 formas de generar imágenes una a partir de texto y otra que a partir de texto y una imagen de base que lo usará como guía. 

![](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.007.png)

Prompt Negativo para todos:

text, logo, watermark, ((bad art)), ((warped)), (((duplicate))), ((morbid)), ((mutilated)), out of frame, extra fingers, mutated hands , badly drawn eyes, ((badly drawn hands)), ((badly drawn face)), (((mutation))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions) )) , cloned face, body out of frame, out of frame, poor anatomy, thick proportions, (deformed limbs), ((arms missing)), ((legs missing)), (((extra arms))), ( (( extra legs))), (fused fingers), (too many fingers), (((long neck))), tiled, poorly drawn, mutated, cross-eyed, canvas frame, frame, cartoon, 3d, weird colors, blurry lowres, pixelated, aliasing, old, granny, ugly, scarey, warped, mutant, butchered, gore, run down, artifacts, mutilated, poorly drawn, poorly detailed, smudged, sketch, pencil, shiny skin, doll, plastic, lowres, poorly drawn, sloppy, overexposed, oversaturated, burnt image, sloppy, broken, blurry, aliasing, cheap, old school, grungy, pixelated, sleepy, closed eyed, low resolution, poorly drawn, crippled, crooked, broken, weird, weird, distorted, erased, cropped, mutilated, sloppy, hideous, ugly, pixelated, aliased,

Prompt Positivo:

**Alta Calidad (Modelo fruitFusion), text2img:**

Bananas realista, Bananas of excellent quality, Yellow colour, Fruits,((High quality)), Fresh, Medium size, Bright yellow, Smooth and slightly firm texture, Sweet and slightly creamy flavor, Light and fruity aroma, No visible spots, No bruises, Perfectly Ripe , Isolated On White Background, Bright Uniform Lighting, Normal Bananas, 8K, Blooming Bananas, Fine Art UHD 4K, Silk Bananas

**Regular Calidad (Modelo CyberRealistic) tex2img:**

Realistic bananas, Low quality bananas, Color yellow, Fruits, ((Low quality)), Fresh, Medium size, Yellow, Soft and slightly firm texture, Sweet and slightly creamy taste, Light and fruity aroma, Visible spots, Bruised, ripe , isolated on white background, bright uniform lighting, normal bananas, 8K, 4K UHD, silk bananas with many spots
**


**Baja Calidad (Modelo CyberRealistic) img2img:**

![](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.008.jpeg)

Bananas realistic, Bananas of very poor quality, poor quality, Color brown, Fruits, ((Poor quality)), not fresh, Medium size, Yellow, Texture smooth and slightly firm, Taste sweet and very creamy, Aroma light and fruity, bananas Rusty, Bruised, Ripe, Isolated On White Background, Bright Uniform Lighting, Regular Bananas, 8K, 4K UHD, Deteriorated Silk Bananas

Steps: 20, Sampler: Euler a, CFG scale: 7, Seed: 4039120947, Size: 512x512, Model hash: 107d2a241b, Model: CyberRealistic, Denoising strength: 0.75

Resultado esperado: 

![Una figura de un plátano

Descripción generada automáticamente con confianza baja](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.009.png)

**Mala Calidad (Modelo CyberRealistic) img2img:**

![](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.010.png)

very poor quality realistic bananas. Bananas should look black, rotten, and badly decayed. They should have a blackish-brown color over their entire surface. The bananas should not look fresh and should show clear signs of spoilage. They should be medium in size and have a smooth but slightly firm texture. Despite their rotten state, they should taste sweet and very creamy. The aroma should be light and fruity, even in the deteriorated state. Bananas should show rusty spots, bruising, and extreme ripeness. The image should be isolated on a white background with bright, even lighting. The bananas should be of a regular shape and size. The desired resolution is 8K or 4K UHD. silk in bananas

Steps: 30, Sampler: Euler a, CFG scale: 7, Seed: 2632735336, Size: 512x512, Model hash: 107d2a241b, Model: CyberRealistic, Denoising strength: 0.75

Resultado esperados y aceptables:  

![](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.011.png)            ![Dibujo de un plátano

Descripción generada automáticamente con confianza media](Aspose.Words.da199446-66e4-4986-9af5-731cbe0c1d8b.012.png)
