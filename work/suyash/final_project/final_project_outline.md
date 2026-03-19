## Scientific Justification
Young star clusters form embedded in dense dust/gas and gradually clear their surroundings through stellar feedback. $\Longrightarrow$ Dust extinction decreases as clusters age.

The timescale for this dust/gas clearing is important for learning about star cluster evolution, dust/gas clearing mechanisms, and feedback models in galaxies.

$H\alpha$ is strongly affected by dust, while $Pa\beta$ is much less affected by dust (longer wavelength = pierces through dust more). $H\alpha = 656 \text{nm}$, $Pa\beta = 1282 \text{nm}$. 

Young clusters = embedded $\Longrightarrow$ low/no $H\alpha$, present $Pa\beta$. Older clusters = clear $\Longrightarrow$ $H\alpha$ and $Pa\beta$ both present.

$\Longrightarrow$ Line ratio of $Pa\beta/H\alpha$ can trace dust extinction.

#### Steps:
- Use archival catalogs (such as [PHANGS-HST](https://archive.stsci.edu/hlsp/phangs)) to get position, ages, and $H\alpha$ for star clusters.
- Observe and measure $Pa\beta$ for those star clusters using positions from catalog.
- Compare $Pa\beta/H\alpha$ line ratio to cluster age $\Longrightarrow$ age at which extinction drops = dust/gas clearing timescale.
- Extra: compare trends in clearing timescale in different sections of galaxy. For example: spiral arms vs core of galaxy?


## Technical Justification
Target: NGC 628 (also called M74 or the Phantom Galaxy).
- Face-on spiral galaxy.
- nearby (<10 Mpc).
- I know there is archival data (my undergrad research advisor worked on it! [example paper](https://iopscience.iop.org/article/10.3847/1538-4357/aa7132/pdf)).
- It can be seen by Gemini North: [photo release](https://noirlab.edu/public/news/gemini0102/).
- Not real reasons: it's really pretty and it's in Pisces which I'm biased for.

Observatory/Instrument:
- Gemini North / NIRI ([source](https://www.gemini.edu/instrumentation/niri/components#Filters))
  - $Pa\beta$ narrowband filter @ 1.282 microns
  - J-continuum narrowband filter @ 1.207 microns

Exposure time:
- I guess I'll need SNR ~8 observations of $Pa\beta$? Default "we are confident in this measurement" SNR (maybe???) 
- Probably can find paper which has observed $Pa\beta$ with Gemini North and use their exposure time as basis.