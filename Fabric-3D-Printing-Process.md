## Introduction to Embedded 3D Printing on Fabric

This process is similar to standard 3D printing with a few key differences.  We'll assume you're already familiar with slicing and other basic concepts covered in previous modules.  Up to the slicing stage, everything remains the same.

**Important:**  Your 3D model should **not** require support structures as  Supports will also be embedded in the fabric and be impossible to remove.

**Follow these steps after slicing your model:**

1. **Navigate to the third layer:** Use the layer preview slider in your slicer software to move to the third layer of your print.
2. **Add a pause:** Right-click on the third layer and select "Add Pause". This will pause the print at the beginning of the third layer.

**After print is paaused**
>⚠️**Caution** - Nozzle temperate is at `205 °C`♨️ and print bed is at `60 °C` ♨️. Be carefull while putting the fabric on the bed.

1. **Raise the Z-axis:**  Use the "Move Z" control(`In tool section`) in 3D printer's interface or fluidd dashboard to raise the print head approximately 100mm. This provides ample space to position your fabric.
2. **Position the fabric:** Place your chosen fabric onto the print bed. Make sure the fabric extends about 1 inch beyond the edges of the print bed on all sides. This extra material allows for easy stretching and securing.
3. **Secure the fabric:** Use 8 paper clips to stretch and secure the fabric to the edges of the print bed. 2 clips should be there on each side
    * **Important:** Fold the handles of the paper clips inward to prevent them from catching on any moving parts.
    * Ensure the fabric lies as flat as possible on the print bed to avoid wrinkles or uneven printing.
4. **Resume printing:** Once the fabric is placed, resume the print. Carefully observe the first layer of printing on the fabric to ensure proper adhesion and quality.
5. **Cool down:** After the print is finished, allow the print bed to cool down completely before removing the fabric. This prevents the printed part from warping or deforming due to heat.

**For Better understanding you can also see below video**

![Fabric Printing Process](./Images/OrcsdlicerFabric%20Printing%20workshop.gif)
