# Force-Directed Network Graphs

This repository presents the results of a rapid systematic review and evidence synthesis analyzing pushback practices and violence towards migrants crossing European borders. The related protocol can be found in the PROSPERO database (Bozorgmehr et al., 2024).

We used force-directed network graphs to visualize the diverse forms of violence and health outcomes reported in the literature. This type of network graph combines three different levels of information:

1. **Word frequency** – expressed by the size of the words
2. **Word relation** – expressed by line thickness (thin to thick), line color (light grey to dark grey), and word spatial distance (distant to close). Spatial distances are adjusted (forced) to increase readability, so exact distances are modified slightly for visual clarity.
3. **Grouping** – expressed by word colors. In this visualization, the color scheme has been applied primarily to ensure readability of closely positioned words rather than to indicate clusters.

The methodology and R implementation are based on a blog post by André Ourednik (2022).

A more detailed description will follow once the publication is ready.

---

## References

*Bozorgmehr, K., Wasko, Z., Knipper, M., Rohleder, S., Boukachabia, A., & Mussa, R.* (2024). Pushback practices and violence towards migrants crossing European borders: Protocol for a rapid systematic review (CRD42022369975). PROSPERO. https://www.crd.york.ac.uk/PROSPERO/display_record.php?RecordID=369975

*Ourednik, A.* (2022, February 4). Text2landscape: Visualize a text in multiple spaces with R—Force-directed networks, biofabric, word embeddings, principal component analysis and self-organizing maps. Ourednik.Info. https://ourednik.info/maps/2022/02/04/text2landscape-visualize-a-text-in-multiple-spaces-with-r-network-visualization-word-embeddings-principal-component-analysis-and-self-organizing-maps/
