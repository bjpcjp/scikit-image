# scikit-image
## notes
	remote: warning: See https://gh.io/lfs for more information.
	remote: warning: File notebooks/applications/plot_3d_interaction.ipynb is 51.11 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
	remote: warning: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.
	remote: 
	remote: Create a pull request for 'master' on GitHub by visiting:
	remote:      https://github.com/bjpcjp/scikit-image/pull/new/master
## notebooks
- applications
	- plot_3d_image_processing.ipynb
		- load & display images
            - data prep (downsampling, normalized spacing)
            - python imshow 3D display error handler
            - imshow 3D workaround (freeze one axis, get 3 pics)
            - display (montage) helper
            - explore slices (jupyter slider widget)
		- adjust exposure
            - gamma correction (brightens/darkens)
            - histogram equalization example
            - explore slices (jupyter slider widget)
            - plot image histograms, before/after equalization
            - clipping pixel values
    		- plotly express
	- plot_3d_interaction.ipynb (kidney tissue)
         - load image
         - imshow example image (slice)
         - use plotly.io.show instead (better results)
         - normalize range per channel
         - explore slices (jupyter slider widget)
         - combine channel facetting and slice animation
 	- plot_3d_structure_tensor.ipynb (Estimate anisotropy in a 3D microscopy image)        - 
	- plot_coins_segmentation.ipynb
	- plot_colocalization_metrics.ipynb
	- plot_cornea_spot_inpainting.ipynb
	- plot_face_detection.ipynb
	- plot_fluorescence_nuclear_envelope.ipynb
	- plot_haar_extraction_selection_classification.ipynb
	- plot_human_mitosis.ipynb
	- plot_image_comparison.ipynb
	- plot_morphology.ipynb
	- plot_pixel_graphs.ipynb
	- plot_rank_filters.ipynb
	- plot_solidification_tracking.ipynb
	- plot_text.ipynb
	- plot_thresholding_guide.ipynb
---
- color_exposure
	- plot_adapt_hist_eq_3d.ipynb
	- plot_adapt_rgb.ipynb
	- plot_equalize.ipynb
	- plot_histogram_matching.ipynb
	- plot_ihc_color_separation.ipynb
	- plot_local_equalize.ipynb
	- plot_log_gamma.ipynb
	- plot_regional_maxima.ipynb
	- plot_rgb_to_gray.ipynb
	- plot_rgb_to_hsv.ipynb
	- plot_tinting_grayscale_images.ipynb
---
- data
	- plot_3d.ipynb
	- plot_general.ipynb
	- plot_scientific.ipynb
	- plot_specific.ipynb
---
- developers
	- plot_max_tree.ipynb
	- plot_threshold_li.ipynb
---
- edges
	- plot_active_contours.ipynb
	- plot_canny.ipynb
	- plot_circular_elliptical_hough_transform.ipynb
	- plot_contours.ipynb
	- plot_convex_hull.ipynb
	- plot_edge_filter.ipynb
	- plot_line_hough_transform.ipynb
	- plot_marching_cubes.ipynb
	- plot_polygon.ipynb
	- plot_random_shapes.ipynb
	- plot_ridge_filter.ipynb
	- plot_shapes.ipynb
	- plot_skeleton.ipynb
---
- features_detection
	- plot_blob.ipynb (Blob detection - 3 alternate algorithms)
	- plot_brief.ipynb
	- plot_censure.ipynb
	- plot_corner.ipynb
	- plot_daisy.ipynb
	- plot_fisher_vector.ipynb
	- plot_gabor.ipynb
	- plot_gabors_from_astronaut.ipynb
	- plot_glcm.ipynb
	- plot_haar.ipynb
	- plot_hog.ipynb
	- plot_holes_and_peaks.ipynb
	- plot_local_binary_pattern.ipynb
	- plot_multiblock_local_binary_pattern.ipynb
	- plot_orb.ipynb
	- plot_shape_index.ipynb
	- plot_sift.ipynb
	- plot_template.ipynb
	- plot_windowed_histogram.ipynb
---
- filters
	- plot_attribute_operators.ipynb (family of contour preserving filtering operations in mathematical morphology)
	- plot_blur_effect.ipynb (estimate blur strength)
	- plot_butterworth.ipynb (butterworth filtering)
	- plot_cycle_spinning.ipynb (Shift-invariant wavelet denoising)
        - **ensure PyWavelets is installed**
	- plot_deconvolution.ipynb (Image deconvolution using the Richardson-Lucy algo)
	- plot_denoise.ipynb (Image denoising with __total variation__, __bilateral__, and __wavelet__ filters)
	- plot_denoise_wavelet.ipynb (Wavelet denoising with VisuShrink & BayesShrink algos)
	- plot_dog.ipynb (Band-pass filtering - Difference of Gaussians)
	- plot_entropy.ipynb (Image entropy)
	- plot_hysteresis.ipynb (hysteresis thresholding vs normal thresholding) 
	- plot_inpaint.ipynb (reconstructing lost or deteriorated parts of images and videos)
	- plot_j_invariant.ipynb (calibrating Denoisers Using J-Invariance)
	- plot_j_invariant_tutorial.ipynb (calibrating Denoisers Using J-Invariance)
	- plot_nonlocal_means.ipynb (Non-local means denoising for preserving textures)
	- plot_phase_unwrap.ipynb
	- plot_rank_mean.ipynb (compares 3 mean filters of the rank filter package)
	- plot_restoration.ipynb (Deconvolve a noisy image using Wiener and unsupervised Wiener algorithms.)
	- plot_tophat.ipynb (Removing small objects in grayscale images with a top hat filter)
	- plot_unsharp_mask.ipynb (linear image sharpening technique)
	- plot_window.ipynb (Image windowing with FFTs)
---
- numpy_operations
	- plot_camera_numpy.ipynb
	- plot_footprint_decompositions.ipynb
	- plot_structuring_elements.ipynb
	- plot_view_as_blocks.ipynb
---
- [registration](https://en.wikipedia.org/wiki/Image_registration)
	- plot_masked_register_translation.ipynb (identify the relative shift between two similar images containing invalid data.)
	- plot_opticalflow.ipynb (Registration using optical flow)
	- plot_register_rotation.ipynb (Using Polar and Log-Polar Transformations)
	- plot_register_translation.ipynb (Use phase cross-correlation to ID the relative shift between two similar-sized images)
	- plot_stitching.ipynb (Assemble images with simple image stitching)
---
- segmentation
	- plot_boundary_merge.ipynb (Hierarchical Merging of Region Boundary RAGs)
	- plot_chan_vese.ipynb (Chan-Vese segmentation. Used for poorly defined boundries.)
	- plot_compact_watershed.ipynb (Find regular segments using compact watershed)
	- plot_euler_number.ipynb
	- plot_expand_labels.ipynb (Expanding segmentation labels without overlap.)
	- plot_extrema.ipynb (Detecting local extrema in an image.)
	- plot_floodfill.ipynb ('paint bucket'.)
	- plot_hausdorff_distance.ipynb (The max distance between any point on the first set and its nearest point on the second set, and vice-versa.)
	- plot_join_segmentations.ipynb (Find the intersection of two segments)
	- plot_label.ipynb (How to segment an image with image labelling)
	- plot_marked_watershed.ipynb (How to build markers for watershed transforms)
	- plot_mask_slic.ipynb (How to compare segmentations obtained with SLIC and its masked version maskSLIC)
	- plot_metrics.ipynb (Evaluating segmentation metrics: watershed vs Canny vs Morphological geodesic)
	- plot_morphsnakes.ipynb (MorphGAC vs MorphACWE for image segmentation)
	- plot_multiotsu.ipynb (Multi-Otsu thresholding)
	- plot_ncut.ipynb (Normalized cuts)
	- plot_niblack_sauvola.ipynb (Niblack and Sauvola thresholding)
	- plot_peak_local_max.ipynb (Finding local maxima)
	- plot_perimeters.ipynb (Perimeter estimation - classic vs Crofton estimators)
	- plot_rag_boundary.ipynb (Region boundary based RAGs)
	- plot_rag_draw.ipynb (Drawing RAGs)
	- plot_rag.ipynb (Demos merge_nodes function of a RAG.)
	- plot_rag_mean_color.ipynb (Build a RAG, then merge regions which are similar in color.)
	- plot_rag_merge.ipynb
	- plot_random_walker_segmentation.ipynb
	- plot_regionprops.ipynb (Explore and visualize region properties with pandas)
	- plot_regionprops_table.ipynb (Measure properties of labelled image regions)
	- plot_rolling_ball.ipynb (Use rolling-ball algorithm for estimating background intensity)
        - **NOTE**: a portion of this notebook uses the pywt package which isn't currently available?
	- plot_segmentations.ipynb (Compares four low-level image segmentation methods)
	- plot_thresholding.ipynb (Create a binary image from a grayscale image)
	- plot_trainable_segmentation.ipynb (Trainable segmentation using local features and random forests)
	- plot_watershed.ipynb (Watershed segmentation)
---
- transform
	- [interpolation: edge modes](notebooks/transform/plot_edge_modes.ipynb)
	- plot_fundamental_matrix.ipynb (fundamental matrix relates corresponding points between a pair of uncalibrated images.)
	- plot_geometric.ipynb (geometric transforms)
	- plot_matching.ipynb (image matching with RANSAC)
	- plot_piecewise_affine.ipynb (piecewise affine transformations)
	- plot_pyramid.ipynb (building image pyramids with pyramid_gaussian)
	- plot_radon_transform.ipynb (sinograms, FBP, SART)
	- plot_ransac.ipynb (line model estimation using RANSAC)
	- plot_rescale.ipynb (rescale, resize, and downscale)
	- plot_ssim.ipynb (structural similarity index)
	- plot_swirl.ipynb (swirl effect)
	- plot_transform_types.ipynb (homographies)
