# CASvsPAS
Supplementary data for our MS 'When the noise goes on: received sound energy predicts sperm whale responses to both intermittent and continuous navy sonar'

Dataset contains two tables
---------------------------
etab = data frame containing exposure sessions <br /> 
mtab = data frame containing min-by-min data <br /> 

Variables definitions
--------------------
Tag_ID = tag deployment identifier <br /> 
Session = sound exposure session type <br />
Start_UTC, End_UTC = start and end time in GMT/UTC <br /> 
Focal = was the whale approached during experiments or not <br /> 
sfromtot = seconds from tag recording start time <br /> 
depth_first = first depth measurements in 1-each one-min time bin <br /> 
depth_mean = average depth measurements over 1-min time bins <br /> 
pitch_mean = circular mean pitch over 1-min time bins <br /> 
RC_prop, BUZZ_prop = proportion time regular clicking / buzz clicking in each bin <br /> 
nBUZZ = number of buzz starts in each bin <br /> 
SLmax, SPLmax, SELmax = maximum source level, received SPL, and received SEL in each time bin <br /> 
SPLmax_incr, SELmax_incr = maximum SLmax, SPLmax, SELmax since the start of the session <br /> 
SPLmax_prev, SELmax_prev, SPLmax_post, SELmax_post, GMOO_tsince, UPAS_tsince = variables defined in Table 2 <br /> 
Lat, Lon = coordinates <br /> 
Bathy_first = bathymetric depth at tag-on time <br /> 
solarnoon = hour since solar noon <br /> 
state = most likely behaviour state <br /> 
NF_prob, LRS_prob = probability (proportion of posterior samples) non-foraging (NF) active state and layer-restricted search (LRS) <br /> 
