# FDM (filament) 3D printing issues and fix them.

## Stringing/Oozing/hairy

> | ![](https://cdn.help.prusa3d.com/wp-content/uploads/2022/02/90014ff5fc80d10b-800x511.jpg) | ![](https://cdn.help.prusa3d.com/wp-content/uploads/2022/02/b1b72c32290b8c00-800x534.jpg) |
> | ------------------- | ------------------ |
> 
> *"Stringing or oozing, also known as "hairy prints", is the name given for when small strings of filament are left on a printed model. This usually happens when the filament keeps flowing from the nozzle while the extruder is moving to another object. You can see this as a marginal line of filament left between the objects. This issue is caused by very* ***high printing temperatures and/or using incorrect retraction settings**"* [2.](https://help.prusa3d.com/article/stringing-and-oozing_1805)
>
> | ![](https://support.bcn3d.com/hs-fs/hubfs/Knowledge%20base/Draft/stringing-gif.gif?width=525&name=stringing-gif.gif) | *"Normally stringing shouldn't happen, however, it will sometimes happen depending on which filament you are using. PET-G is notorious for stringing, and hygroscopic materials such as TPU or Nylon may have stringing issues if they are not well-conditioned. There are many ways to fix stringing. Luckily, it's quite easy to solve. Let's look at all the variables that can influence stringing."* [1.](https://support.bcn3d.com/knowledge/stringing)  |
> | ------------- | --------------- |

### Common Solutions
- Enabling retraction 
  - Retraction speed:  1200-6000 mm/min (20-100 mm/s)
  - Retraction Distance: If you increase its value, it will reduce stringing, but if you increase it too much, your print will have gaps
- Prime: This movement pushes the filament back in the nozzle exit so it can continue extruding
  - Prime speed: If it's too fast, oozing will also occur at the start of the extrusion path, leaving behind a blob of filament. 
- Temperature is too high: try decreasing your extruder temperature by 5-10 degrees
- Long movements over open spaces
- Movement Speed:  If your machine can handle moving at higher speeds, you may find that increasing these settings can also reduce stringing between parts.

- [Prusa slicer settings](https://help.prusa3d.com/article/stringing-and-oozing_1805)
- [Cura settings]()

-----------------------------

# Bibliography
- [1. - How to fix Stringing/Oozing](https://support.bcn3d.com/knowledge/stringing)
- [2. - Stringing and oozing](https://help.prusa3d.com/article/stringing-and-oozing_1805)
- [3. - ]()
