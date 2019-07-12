# Yelp Maps Project
In this project, we will create a visualization of restaurant ratings using machine learning and the Yelp academic dataset. In this visualization, Berkeley is segmented into regions, where each region is shaded by the predicted rating of the closest restaurant (yellow is 5 stars, blue is 1 star). Specifically, the visualization we will be constructing is a Voronoi diagram.

In the map below, each dot represents a restaurant. The color of the dot is determined by the restaurant's location. For example, downtown restaurants are colored green. The user that generated this map has a strong preference for Southside restaurants, and so the southern regions are colored yellow.

![](demo.gif)

## How To Start 
  ```bash
  $> git clone https://github.com/phuocthevo/maps.git
  ```
  ```bash
  $> python recommend.py
  ```

## License
[MIT](./LICENSE)
