# Annotated Driving Dataset - Poland

Note: The dataset is free to use. It's annotated manualy and could contain errors.

## Dataset

The dataset includes driving in Poland (currently Warsaw only) during daylight and nightlight conditions. The images are captured using car dashcams running at full resolution of 1920x1200. From the video files two frames per second are captured as images. The dataset is annotated manualy by [Sethai](https://github.com/sethai) using the Microsoft [VOTT](https://github.com/microsoft/VoTT) software

### Sample images:
![](./images/car_1.jpg)
![](./images/car_2.jpg)
![](./images/car_3.jpg)
![](./images/car_4.jpg)

### Dataset download

<table>
    <tr>
        <td>Size</td>
        <td>2.8 GB</td>
    </tr>
    <tr>
        <td>Download</td>
        <td><a href="http://konradobah.pl/www/dataset_poland/dataset.zip">dataset</td>
    </tr>
</table>

#### Labels
- car
- truck
- Pedestrian
- trafficlight
- trafficlight-green
- trafficlight-red
- trafficlight-yellow
- crosswalk
- bicycle
- biker
- dog
- stop-sign

#### CSV Format
- image name
- xmin
- ymin
- xmax
- ymax
- label
- time of day

#### Labels count

![](./images/labels_count.jpg)

<table>
    <tr>
        <td>car</td>
        <td>8640</td>
    </tr>
    <tr>
        <td>truck</td>
        <td>1221</td>
    </tr>
    <tr>
        <td>pedestrian</td>
        <td>1186</td>
    </tr>
    <tr>
        <td>trafficlight</td>
        <td>802</td>
    </tr>
    <tr>
        <td>trafficlight-green</td>
        <td>399</td>
    </tr>
    <tr>
        <td>trafficlight-red</td>
        <td>323</td>
    </tr>
    <tr>
        <td>crosswalk</td>
        <td>261</td>
    </tr>
    <tr>
        <td>bicycle</td>
        <td>72</td>
    </tr>
    <tr>
        <td>trafficlight-yellow</td>
        <td>19</td>
    </tr>
    <tr>
        <td>biker</td>
        <td>12</td>
    </tr>
    <tr>
        <td>dog</td>
        <td>6</td>
    </tr>
    <tr>
        <td>stop-sign</td>
        <td>4</td>
    </tr>    
</table>
