# Measuring_Halpha_IFU
IFU Data to measure the emission lines flux with real data


Los datos archivos que están ahí son de la galaxia NCG5947 tomados por el survey Califa con un telescopio de 3.5 metros en España. La descripción de los archivos es la siguiente:

NGC5947.V500.rscube.fits.gz: Datos de espectroscopía de campo integral (IFU) ---> Cada pixel de la imágen es un espectro.

Ahora bien, si yo mido el flujo en cada pixel de H$\alpha$ (por ejemplo) encontraré una imagen como la del archivo NGC5947_flux_Ha.fits.

integ_3D.fits & integ_3D.txt: La suma integrada de todos los espectros del archivo anterior para obtener un sólo espectro ---> Esto equivale a un dato del SDSS.

 integ_3D.pdf: La gráfica del espetro descrito anteriormente

Los datos básicos de esa galaxia los puedes encontrar acá: https://ned.ipac.caltech.edu/cgi-bin/objsearch?objname=NGC5947&extend=no&hconst=73&omegam=0.27&omegav=0.73&corr_z=1&out_csys=Equatorial&out_equinox=J2000.0&obj_sort=RA+or+Longitude&of=pre_text&zv_breaker=30000.0&list_limit=5&img_stamp=YES