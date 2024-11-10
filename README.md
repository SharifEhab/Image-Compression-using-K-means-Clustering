
# Image Compression Using K-Means Clustering

AndrewNG programming Assignment ML Specialization Unsupervised Learning

### How It Works

1. **Pixel Grouping**: K-Means clustering groups pixels with similar colors in an image into a specified number of clusters.
2. **Centroid Representation**: Each cluster is represented by the color of its centroid, which replaces all colors in that cluster, reducing the total number of unique colors.
3. **Image Reconstruction**: The original image is reconstructed using only the cluster centroids, effectively compressing the image by reducing color variability.

### Key Concepts

- **K-Means Clustering**: An unsupervised learning algorithm that partitions data into K clusters. It minimizes within-cluster variance by iteratively updating cluster centers (centroids) and reassigning data points (pixels) to the closest centroid.
- **Image Compression**: By reducing the number of colors in an image, file size is reduced, making it easier to store or transmit.

### Why Use K-Means for Image Compression?

- **Efficient Compression**: K-Means clustering provides a simple yet effective way to reduce the number of unique colors in an image, leading to a lower storage requirement.
- **Preserved Visual Quality**: Although the image is compressed, the quality remains relatively high, as similar colors are grouped, maintaining the visual content of the original image.
- **Adjustable Compression Levels**: The number of clusters (K) can be tuned to control the level of compression, balancing file size and image quality.

## Example of Image Compression

The image below shows the result of compressing an image using K-Means clustering:

![image](https://github.com/user-attachments/assets/39d84494-e3f0-4179-8f6f-9fa959b6a501)


As the number of clusters (K) decreases, the file size reduces, but the image starts losing some of its original details. A higher K preserves more details but results in a larger file.

## Advantages of K-Means Image Compression

- **Simple Implementation**: The algorithm is easy to implement and can be applied to various image formats.
- **Customizable Compression**: By adjusting the number of clusters, the desired level of compression and quality can be achieved.
- **Reduced File Size**: K-Means clustering can substantially reduce file size, making it useful for applications where storage or bandwidth is limited.

---
