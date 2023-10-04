# TTTTutorial

## Reducing Data Size by Volume Spliting

---

Large Data sets pose a problem for 3D slicer. Use this tutorial to reduce data size 

1. Import data using **ImageStacks** module in **SlicerMorph** extension

	1. Import at full resolution
	2. See [ImageStacks Tutorial](https://github.com/SlicerMorph/Tutorials/tree/main/ImageStacks)
	
2. Select only your specimen using *Threshhold* tool in **Segment Editor** module
	
	1.  Add a segment
	2. Select **Threshhold** (hotkey 2)
	3. Set threshholding Range by lasso using right-clicking with mouse over desired region in your slice followed by fine tuning using the slider under the Threshhold Range tab
	4. Once satisfied with thresholding select **Apply**
	
	![](/TTTTutorial/splitvolume1/splitvolume1.001.png)
	
3. Generate Volume of Interest from Segment using **SplitVolume** tool

	1. Select **Split Volume** tool
	2. Select pad voxel number
	3. Select *Apply*
	
	
	![](/TTTTutorial/splitvolume2/splitvolume2.001.png)
	
4. Save new Volume

