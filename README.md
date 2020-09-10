# MSFS TBM 930 Project version 0.3
This is the improvement project for the MSFS default TBM 930.

Current features of this modification are:

**Removed the 30% gap between 0 and 30% throttle:**

tp_high_idle_throttle_pos = 0; *(default = 30)*

...so then I needed to ajust:

n1_to_shaft_torque_table = ... 68:0.12, 87:0.88 ...

**Ajusted ITT slightly:**

itt_peak_temperature = 1150 *(default = 2100)*

itt_tuning_constant = 2 *(default = 1)*

**Ajusted autopilot maximum pitch:**

max_pitch = 15 *(default = 10)*

**Corrected some numbers:**

pitch_takeoff_ga = 10 *(default = 8)*

min_n1_for_starter_cutoff = 52 *(default = 50)*

min_n2_for_starter_cutoff = 80 *(default = 200)*

rated_shaft_hp = 850 (default = 0)

CG_aft_limit = 0.355 *(default = 0.36)*

rotation_speed_min = 80 *(default = 90)*

cruise_alt = 31000 *(default = 30000)*

best_glide = 120 *(default = 0)*

**Corrected torque vs air density:**

density_on_torque_table = ... 0.000975:0.965, 0.002378:0.965

**Landing gear creates more drag (by [PositiveZero](https://forums.flightsimulator.com/u/positivezero/summary)):**

drag_coef_gear = 0.04700 *(default = 0.01000)*

**Ajusted inertial separator decrease in torque to half:**

(L:XMLVAR_InertSep#ID#_Deployment) 8192 * (&gt;K:ANTI_ICE_GRADUAL_SET_ENG#ID#) (default = 16384)

## Known Issues:

- Still testing fuel consumption. If you enconter any problems, let me know.

My Discord: Guilherme Farias#9971

My forum profile: [GuiFarias31](https://forums.flightsimulator.com/u/guifarias31/summary)

## How to Install:

1: Click on the green button in the top right corner that says 'Code' and click "Download as ZIP"

2: Unzip and put the folder "aircraft-tbm930-performance" in your MSFS Community folder

For more liveries see this thread: https://forums.flightsimulator.com/t/turboprop-master-livery-list/168196/16
