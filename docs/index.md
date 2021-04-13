Accompanying website for "Quality Diversity for Synthesizer Sound Matching" submitted to DAFx 2020in21 (2021)


## Animation of the Evolution

The histogram of population in BC space during a typical run is shown below. Bins with lighter color has the most individuals. The x axis is the spectral flatness (dB) and the y axis is spectral centroid (Hz). As can be seen from the animation, methods with novelty objective (NS-GC, NS-LC) explores a wider region, leading to the discovery of diverse solutions.

### GA

<video width="500" height="500" controls="controls">
  <source src="video/ga_nsynth_0.mp4" type="video/mp4">
</video>

### NS-GC

<video width="500" height="500" controls="controls">
  <source src="video/nsgc_nsynth_0.mp4" type="video/mp4">
</video>

### NS-LC

<video width="500" height="500" controls="controls">
  <source src="video/nslc_nsynth_0.mp4" type="video/mp4">
</video>

## Parameter Estimation

We show the results of sound matching (parameter estimation) with Dexed (in the synthesizer settings medium and large) and u-he Diva using GA/NS-GC/NS-LC. It can be deduced from the results of Dexed-Large that the large setting with vibrato enabled abused the vibrato feature to obtain a flat spectra to achieve better log-spectral distortion.

WARNING: VERY LOUD SOUNDS INCLUDED! (sometimes clipping)

### Dexed Medium

<table>
    <thead>
        <tr>
            <th colspan="4">In-domain (DX7 preset)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Original</td>
            <td>GA</td>
            <td>NS-GC</td>
            <td>NS-LC</td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/medium/dexed/3_o.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/3_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/3_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/3_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/medium/dexed/24_o.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/24_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/24_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/24_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/medium/dexed/26_o.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/26_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/26_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/dexed/26_nslc.mp3"></audio></td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th colspan="4">Out-of-domain (Nsynth Dataset))</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Original</td>
            <td>GA</td>
            <td>NS-GC</td>
            <td>NS-LC</td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/medium/nsynth/2_o.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/2_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/2_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/2_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/medium/nsynth/5_o.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/5_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/5_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/5_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/medium/nsynth/13_o.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/13_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/13_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/medium/nsynth/13_nslc.mp3"></audio></td>
        </tr>
    </tbody>
</table>

### Dexed Large

<table>
    <thead>
        <tr>
            <th colspan="4">In-domain (DX7 preset)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Original</td>
            <td>GA</td>
            <td>NS-GC</td>
            <td>NS-LC</td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/large/dexed/3_o.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/3_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/3_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/3_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/large/dexed/24_o.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/24_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/24_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/24_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/large/dexed/26_o.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/26_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/26_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/large/dexed/26_nslc.mp3"></audio></td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th colspan="4">Out-of-domain (Nsynth Dataset))</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Original</td>
            <td>GA</td>
            <td>NS-GC</td>
            <td>NS-LC</td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/large/nsynth/2_o.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/2_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/2_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/2_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/large/nsynth/5_o.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/5_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/5_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/5_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/large/nsynth/13_o.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/13_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/13_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/large/nsynth/13_nslc.mp3"></audio></td>
        </tr>
    </tbody>
</table>

### Diva

<table>
    <thead>
        <tr>
            <th colspan="4">Out-of-domain (Nsynth Dataset))</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Original</td>
            <td>GA</td>
            <td>NS-GC</td>
            <td>NS-LC</td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/diva/2_o.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/2_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/2_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/2_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/diva/4_o.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/4_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/4_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/4_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/diva/13_o.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/13_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/13_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/13_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/diva/24_o.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/24_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/24_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/24_nslc.mp3"></audio></td>
        </tr>
        <tr>
            <td><audio controls src="assets/match/diva/26_o.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/26_ga.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/26_nsgc.mp3"></audio></td>
            <td><audio controls src="assets/match/diva/26_nslc.mp3"></audio></td>
        </tr>
    </tbody>
</table>

## Quality-Diversity

<img src="assets/trumpet_map.png" alt="hi" class="inline"/>

Original (Out-of-domain electronic keyboard sound):

<audio controls src="assets/app/orig.ogg">
</audio>

Best match (Red point in the BC space):

<audio controls src="assets/app/best.ogg">
</audio>

Bright (Pink):

<audio controls src="assets/app/bright.ogg">
</audio>

Pure (Brown):

<audio controls src="assets/app/pure.ogg">
</audio>

Noisy (Orange):

<audio controls src="assets/app/noise.ogg">
</audio>
