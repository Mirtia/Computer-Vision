## Why Pinhole Camera?

- Educational Purposes

![[Pasted image 20240722141438.png]]**Figure 1**. The simplicity of the Pinhole Camera model

- Artistic Purposes

![[Photography-Art.png]]
**Figure 2**. Example of Pinhole photography [Cameron Gillie ](https://thepinholething.com/pinhole-photography/)

### Pinhole and Perspective Projections

![[Image-Formation.png]]

>You cannot see an image being formed, because the screen receives light from a lot of different points, causing overlapping of light rays, making it impossible to see a clear image being formed.


![[Focal-Length.png]]

- *"...z-axis points toward the image plane and lies on the optical axis..."*
  *Optical axis:* axis perpendicular to the image plane

- *Effective focal length*: The distance between the pinhole and the image plane

>Two triangles are **similar** if they have the same shape but not necessarily the same size. The corresponding angles are equal, and the corresponding sides are **proportional**. We can think of one similar triangle as an enlargement or a reduction of the other. (See [Similar Triangles](https://math.libretexts.org/Bookshelves/Precalculus/Trigonometry_(Yoshiwara)/01%3A_Triangles_and_Circles/1.01%3A_Similar_Triangles)).
>
>Because they are proportional we can derive the following formula:
> $$ \frac{a}{a'} = \frac{b}{b'} = \frac{c}{c'}$$

### Image Magnification

![[Image-Magnification.png]]

- Applying Perspective Projection:

![[Perspective-Projection.png]]

- Magnification
$$ 
|m| = |\frac{f}{z_0}|
$$
- Image size inversely proportional to depth!

### Visualizing the Effect

Imagine a pinhole camera capturing an image of a tall building. If the screen is 2 meters behind the pinhole, you get a smaller but possibly brighter and sharper image. Moving the screen to 4 meters increases the image size, showing more detail of the building but potentially reducing sharpness and brightness, requiring adjustments in exposure time.

### Finding the Vanishing Point

![[Vanishing-Point.png]]

### Ideal Pinhole Size

![[Pinhole-Camera-Size.png]]

- Ideal size of the pinhole:
$$d\approx 2\cdot \sqrt{f \cdot λ}$$
*f*: effective focal length
*λ*: wavelength

- Pinhole cameras require long exposures to capture bright images

## Lenses

Lenses follow the same projection model but they manage to gather significantly more light than the pinhole camera.

![[Lenses.png]]

- Gaussian Lens Law

### Two-Lenses System

![[Multiple-Lenses.png]]

- *Zooming*: Move lenses to change magnification

- *Aperture* can be reduced/increased to control image brightness (light receiving area of lens, indicated by lens diameter) 

- $D =  \frac{f}{N}$ 

- *f-Number:* $N = \frac{f}{D}$

- *Plane of Focus*

- Move the image plane, the lens, or both to focus on specific point

### Depth of Field

- One plane in the scene that is perfectly focused

- Degree of defocus increases with its distance from the plane of focus, get progressively out of focus

- The blur circle lies within a single pixel -> smaller than the size of a pixel (depth of field of the imaging system)

- [A Simple Guide to Depth of Field - YouTube](https://www.youtube.com/watch?v=34jkJoN8qOI) (Very good and simple explanation with drawings)
