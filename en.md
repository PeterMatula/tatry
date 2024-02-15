# Map of the Tatra Mountains

[🇸🇰 Slovensky](README.md)

The goal of the *Map of Tatra Mountains* project is to create an amazing map of the highest Slovak and Polish mountain range, which will be:

* *free*: available for free, subject to compliance with simple [license terms](#license-and-copyright)
* *modern*: shared in an arbitrarily scalable vector format
* *detailed*: containing a large amount of geographic data
* *accurate*: corresponding (with few [exceptions](#about-the-map)) to the real world
* *complete*: showing the entire mountain range, not just its central/Slovak part
* *mountaineering*: containing all locations important for climbing and mountaineering

In short, the map wants to be a work of art that, when hung on the wall, will bring joy to lovers of the Tatras. At the same time, you can use it when planning your next adventure.

The map is only available in electronic form. It is not in the author's power, nor to the taste, to arrange its physical production and distribution. You can download the map and have it printed at the nearest copy center. If you like the result, you can [reward](#Support) the author at your discretion.

## Download

| Version | Font | A0 PDF | A1 PDF | Notes |
|  :---: | :---:|  :---: |  :---: |  :---: |
|  [1.0](https://github.com/PeterMatula/tatry/releases/tag/v1.0)  | typeface |   [📥 download](https://github.com/PeterMatula/tatry/releases/download/v1.0/tatry-v1_0-ubuntu-A0.pdf)  |   [📥 download](https://github.com/PeterMatula/tatry/releases/download/v1.0/tatry-v1_0-ubuntu-A1.pdf)  | [changelog](https://github.com/PeterMatula/tatry/blob/main/CHANGELOG.md#v10-2024-02-11) |
|  [1.0](https://github.com/PeterMatula/tatry/releases/tag/v1.0)  | handwritten |   [📥 download](https://github.com/PeterMatula/tatry/releases/download/v1.0/tatry-v1_0-virgil-A0.pdf)  |   [📥 download](https://github.com/PeterMatula/tatry/releases/download/v1.0/tatry-v1_0-virgil-A1.pdf)  | [changelog](https://github.com/PeterMatula/tatry/blob/main/CHANGELOG.md#v10-2024-02-11) |

The table contains several versions of the map. Choose the one that you like best. Whichever one you choose, have it printed in color, in the highest possible quality (dpi), on a quality printer, and paper of reasonable quality/thickness. A good copy center will certainly be happy to advise you.

The primary map format is A0. If this size is too big for you, you can use the A1 format (here I would choose a more readable font, see below). Going to even smaller sizes makes no sense, the text will become unreadable. On the other hand, with a little technical skill, you can scale up the map to any size without losing quality. For example, to the full width (approx. 90 cm, total size approx. 160 x 90 cm) of commonly available large-format printers. Or you can use the map to wallpaper your living room or put it on a highway billboard, vector graphics don't care.

Furthermore, the map is available in two font versions. In the classic, typeface and more readable sans-serif font [Ubuntu](https://fonts.google.com/specimen/Ubuntu). And in a daring, hand-written, less legible, but overall very well-fitting font [Virgil](https://virgil.excalidraw.com/) (the author's favorite).

The last division is into versions. The first public version is `v1.0`, its fixes and small improvements will be `v1.X`, and any future major changes `vX.Y`.

## Support

The author will be grateful if you [inform](#contact) him of any errors and imperfections you discover. There will certainly be many of them, but together, we can gradually fine-tune the artwork. Before sending your comment, please read the chapter [About the map](#about-the-map).

If you like the artwork and want to reward the author financially, you can send any amount to one of these accounts:

* EUR € účet
   * Account holder: Peter Matula
   * IBAN: BE10 9677 7301 6204
   * SWIFT/BIC: TRWIBEB1XXX
   * Bank address: Rue du Trône 100, 3rd floor, Brussels 1050, Belgium
   * SEPA transfer QR code (edit the amount as you wish)\
     ![image](https://github.com/PeterMatula/tatry/assets/20342097/8f6cbe5b-1a64-479a-9bf1-3ee32def0504)
* Bitcoin: `bc1qtfllkv65rtdvvvrrjquy46yj7cduzw3urlrrv7` ([QR code](https://github.com/PeterMatula/tatry/assets/20342097/dd5ee979-89fc-44c6-90ee-2273e97229b4))


Thank you \
Peter Matula (author)

## License and Copyright

Copyright © Peter Matula and © OpenStreetMap (more details in [About the map](#about-the-map) Section).

All the above-listed artworks are licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.en).

In short, you can freely copy and redistribute the artwork in any medium or format (e.g. print it). The author does not wish, and the license does not allow, any modifications of the artwork or its commercial use.

If you are in doubt, or you would like to use the artwork under different conditions, please [contact](#contact) the author.

## About the map

The concept of the map is to show, in the most beautiful way, the ridges, peaks, and saddles recorded in the monograph of Arno Puskáš and other mountaineering sources. Other basic layers such as lakes, streams, hiking trails, etc. are of course also included. The wonderful old map by Mr. Hlaváček was a significant inspiration. However, the new map does not attempt to deal with the foothills, it focuses only on the mountain range itself. There are currently other better means of orientation in the city or on the road. Furthermore, it does not only focus on the central part of the mountain range or its Slovak part, it shows the entire High and Belianske Tatras. In the future, when the author takes a break and gathers enough strength, enthusiasm, and time, maybe he will continue mapping the Western Tatras. The shape of the Tatras is extremely favorable. The Western Tatras immediately connect in a purely western direction, so their mapping would not only produce their separate map but also, the possibility of a truly impressive joint map of the entire Tatras range.

The currently mapped area has an area of 28 by 16 kilometers, which gives it a suitable aspect ratio of 1.75:1. The amount of displayed information determines the minimum printed, physical size of the map. A0 is ideal, A1 is (with good eyesight) readable. A much smaller size does not make sense. Upwards, the size is not limited, although a significant format change might require specific changes to keep the map looking good (for example, tweaking the font size).

Thanks to the technique of its creation (see below), the map corresponds quite accurately to the real world. From a general point of view, the distances and characteristic features of the objects are not significantly distorted (if they are, this is a bug that you can report). But for the map to look as beautiful as possible, it was necessary to smooth out the details at the local level, solve problems, and adapt the real objects' coordinates to the map concept. For example, ridges are displayed as rounded, gracefully connecting lines of variable thickness. If the real ridge makes a sharp turn somewhere, the map generation algorithm will smooth it out to some extent. If there is a peak or a saddle on such a ridge, the algorithm will move it slightly so that it still lies on the smoothed ridge. Other types of objects, such as streams, rivers, and walls, are similarly smoothed. Another example is the peak and saddle positions. The original underlying data places them as accurately as possible to their real positions. In the resulting map, however, the object symbols have certain sizes, the peak, for example, a white circle of variable radius. If this assigned radius is greater than the nearest neighbor distance, the objects would overlap as a result. Again, when generating the output graphics, similar objects are moved further apart, often for example many peaks and saddles are spread over a larger section of the ridge. Similar micro-modifications are applied to almost every map object, and without a significant change in map style, it is impossible to avoid them. However, the names, order, properties, relationships, etc. of the objects must match the reality. If it doesn't fit, don't hesitate to report the problem.

Despite the relatively large format of the map, its capacity to hold information is not unlimited, nor is it sufficient in all cases. For this reason, some less important objects were neglected, especially in already crowded areas. Therefore, if you have come across a missing geographic object, before reporting it, please consider whether it is even realistic to add it to the appropriate location. Furthermore, for aesthetic reasons, some layers were deliberately reduced (for example streams), and some geometries were simplified or completely omitted (for example, tourist crossings, refreshments, or attractions). The goal is not to overwhelm the map with information even in places that still have the capacity to hold more information. Priority is given to natural objects and climbing locations. If you hesitate to report a missing object, feel free to let the author know, at worst it will not be added. If you find an error in the existing objects, be sure to contact the author.

Much, much effort has been put into an ideal and eye-pleasing label layout. But there is still room for improvement on this front. If you have any ideas on how to improve the typography, let's hear them. The author loves typography. I believe that any new version of the map will be a step for the better. Here, it is appropriate to mention that the author, after much consideration, has decided not to include the objects' elevations. Their indiscriminate presence would overwhelm the map with a bunch of extra text and make it look ugly overall. Their presence in future versions is not inconceivable, but much more work would have to be invested to make it look good.

Another nut to crack is Slovak vs Polish in the captions. For now, the author has decided to use Slovak labels on Slovak territory, Polish labels in Poland, and Slovak on the border (after all, the author is Slovak). If this rule is not obeyed somewhere, it is an imperfection that can be reported for repair. In such a case, however, it would be useful to specify not only what to repair, but also for what - what is the correct name of the given object and, ideally, a reliable source of the name. Another possible future improvement is the production of a Polish version of the map, both in terms of names on the border or even in the whole Tatras (if there even are Polish names for all objects). Whether the author will ever get to something like this is in the stars.

The map was created by manually drawing all geographic objects collected from the sources listed below on the underlying orthophoto layer of the selected territory. The author of the map is therefore the only author of all underlying geodata from which the map is generated. However, the data itself was collected from other sources. This procedure was chosen for several reasons:

* Many required geographic objects are not available at all (for example ridges) or not available in sufficient quantity (for example peaks, saddles) from open sources (for example [OSM](https://www.openstreetmap.org/)).
* It turned out that even where free resources contain all the necessary geographical objects (for example, streams, rivers, lakes), very laborious additional processing is necessary after their import. As a result, it turned out to be easier to redraw these objects as required by the map's style.
* In the few cases where free resources were practically usable (for example hiking trails), the author decided, for incomprehensible reasons, to draw his own layers anyway. It is therefore not surprising that the creation of the map took about 4 years.

The map was created in [QGIS](https://qgis.org/en/site/).

Sources:

* Arno Puškáš: Monograph Vysoké Tatry.
* OpenStreetMap - OSM geodata were not used directly, author thinks [this](https://wiki.openstreetmap.org/wiki/Open_Data_License/Use_Cases#Using_OSM_data_for_the_production_of_a_hand-made_map) and [this](https://osmfoundation.org/wiki/Licence/Licence_and_Legal_FAQ#4._CAN_I_USE_OSM_DATA_AND_OPENSTREETMAP-DERIVED_MAPS_TO_VERIFY_MY_OWN_DATA_WITHOUT_TRIGGERING_SHARE-ALIKE?) applies. Just to be sure, OSM copyright has been added in the [Licencia a Copyright](#license-and-copyright) Section.
* [tatry.nfo.sk](https://tatry.nfo.sk/)
* 
## Contact

Peter Matula \
[tatry.mapa@gmail.com](mailto:tatry.mapa@gmail.com)
