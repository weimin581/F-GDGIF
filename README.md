Guided image filtering (GIF) based cost aggregation or disparity refinement stereo matching algorithms are
studied extensively owing to the edge-aware preserved smoothing property. However, GIF suffers from halo
artifacts in sharp edges and shows high computational costs on high-resolution images. The performance of GIF
in stereo matching would be limited by the above two defects. To solve these problems, a novel fast gradient
domain guided image filtering (F-GDGIF) is proposed. To be specific, halo artifacts are effectively alleviated by
incorporating an efficient multi-scale edge-aware weighting into GIF. With this multi-scale weighting, edges can
be preserved much better. In addition, high computational costs are cut down by sub-sampling strategy, which
decreases the computational complexity from O(N) to O(N/s2
) (s: sub-sampling ratio) To verify the effectiveness
of the algorithm, F-GDGIF is applied to cost aggregation and disparity refinement in stereo matching algorithms
respectively. Experiments on the Middlebury evaluation benchmark demonstrate that F-GDGIF based stereo
matching method can generate more accuracy disparity maps with low computational cost compared to other
GIF based methods.
