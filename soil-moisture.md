You will need:
- micro:bit V2
- Design & Automate Accessory Kit (breakout board, three alligator clips and the Kitronik soil sensor)

## Step 2
Go to **Extensions** in the block menu, search for **Design & Automate** and add it. You will now see the Design & Automate blocks in your menu.

## Step 3
Go to **Variables** and click **Make a Variable**. Name it **Soil Moisture** and click OK.

## Step 4
In the ``||basic:on start||`` block add a ``||variables:set Soil Moisture to||`` block and set the value to **0**.

## Step 5
Add a ``||basic:forever||`` block. Inside it add a ``||variables:set Soil Moisture to||`` block and connect the **soil prong moisture** block from the Kitronik FarmBeats category.

## Step 6
Add a ``||basic:show number||`` block and drop the **Soil Moisture** variable into it.

## Step 7
Add a ``||basic:pause (ms)||`` block set to **500**.

## Step 8
Add a ``||basic:clear screen||`` block.

## Step 9
Add a final ``||basic:pause (ms)||`` block set to **5000**. This waits 5 seconds before taking the next reading.

## Step 10 @showdialog
Your program is complete! Download it to your micro:bit, insert the soil sensor into soil, and watch the moisture reading scroll across the LED display.

- Low number (0-300) = dry soil
- Middle number (300-600) = moist soil
- High number (600+) = wet soil
