# Movements Catalog

This catalog lists **every movement currently defined in the SDK** and the string you should pass to the API to enable it. It’s organized by category so developers and customer stakeholders can quickly find what’s supported and how to use it efficiently.

## How to read this
- **Movement** — human-friendly name.  
- **SDK String** — the exact identifier to use when configuring the SDK.  
- **Description** — short guidance on form and intent (added where it wasn’t present in the CSV).  
- **Body Zone** — primary regions involved.  
- **Preferred View** — recommended camera orientation for best tracking (Front/Side).  
- **Video** — ✓ = instruction video available, ⏳ = coming soon.  

> **Side notation.** Variants labeled *(left/right)* or with `Left/Right` in the SDK string are tracked per side. When relevant, create two sets (one per side) to capture balanced metrics.  

> **Rest and Cooldown detectors.**  
> The SDK also supports **detectors of type `Rest`** and **`Cooldown`**.  
> - `Rest` can be used to explicitly represent rest periods between active exercises, allowing the SDK to recognize and utilize these intervals in structured workout flows.  
> - `Cooldown` can be used at the end of sessions to track passive or low-intensity phases, enabling smoother transitions and accurate session summaries.

## General capture recommendations
- Keep the **full body in frame**; camera at ~hip to chest height, lens facing the user.  
- Stand **2–3 m** from the camera for standing movements; **1.5–2 m** for floor work.  
- Prefer **Front** view for bilateral/symmetry checks and **Side** view for hinge, push-up, and plank mechanics.  
- Use even lighting; avoid strong backlight.  

---

## Dynamic

| Movement | SDK String | Description | Body Zone | Preferred View | Video |
| --- | --- | --- | --- | --- | --- |
| Air Squat | SquatRegular | Bodyweight squat to ~parallel, feet shoulder-width, neutral spine. | Lower | Front | ✓ |
| Alternate Windmill Toe Touch | AlternateWindmillToeTouch | Standing hip hinge with rotation; alternate hand to opposite foot. | Back, Hamstrings | Front | ✓ |
| Burpees | Burpees | Squat to plank (option push-up) then snap in and jump. | Lower, Upper | Front | ✓ |
| Crunches | Crunches | Supine trunk flexion targeting the rectus abdominis. | Abs | Side | ✓ |
| Forward Lunge (Right) | LungeFrontRight | Step forward with right leg; descend until both knees ~90°; drive back. | Lower | Side | ✓ |
| Forward Lunge (left) | LungeFrontLeft | Step forward with left leg; descend until both knees ~90°; drive back. | Lower | Side | ✓ |
| Froggers | Froggers | From plank, jump feet outside hands and back—hips low, chest up. | Lower, Upper, Abs | Front | ✓ |
| Glutes Bridge | GlutesBridge | Supine hip extension; squeeze glutes at top with neutral ribs. | Back, Lower | Side | ✓ |
| High Knees | HighKnees | Run in place driving knees to hip height; quick ground contacts. | Lower | Front | ✓ |
| Jumping Jacks | JumpingJacks | Jump feet wide while arms overhead, then return. | Lower, Upper | Front | ✓ |
| Jumps | Jumps | Bilateral vertical jumps with soft landing. | Lower | Front | ✓ |
| Lateral Raises | LateralRaises | Shoulder abduction to ~90°; control up/down (bodyweight or light load). | Upper | Front | ✓ |
| Narrow Squat | SquatNarrow | Squat with feet hip-width or narrower to emphasize quads. | Lower | Front | ⏳ |
| Overhead Squat | SquatRegularOverhead | Dynamic squat with arms locked overhead; keep torso upright. | Back, Upper, Lower | Front | ⏳ |
| Plank Shoulder Taps | PlankHighShoulderTaps | From high plank, alternate tapping opposite shoulder without hip sway. | Upper | Front | ✓ |
| Pushup Knees | PushupKnees | Push-up from knees for reduced load; chest to floor, elbows ~45°. | Upper, Abs | Side | ⏳ |
| Pushup Knees Narrow | PushupKneesNarrow | Knee push-up with hands narrow; emphasizes triceps. | Upper, Abs | Side | ⏳ |
| Pushup Knees Wide | PushupKneesWide | Knee push-up with wider hands; emphasizes chest. | Upper, Abs | Side | ⏳ |
| Pushup Narrow | PushupNarrow | Standard push-up with hands under shoulders or closer; triceps-biased. | Upper, Abs | Side | ⏳ |
| Pushup Wide | PushupWide | Standard push-up with wider hand placement; chest-biased. | Upper, Abs | Side | ⏳ |
| Pushups | PushupRegular | Standard push-up; braced core, full range. | Upper | Front | ✓ |
| Reverse Sit To Table Top | ReverseSitToTableTop | From seated, press hips up to reverse tabletop; shoulders open. | Back, Upper, Lower | Side | ✓ |
| Shoulders Press | ShouldersPress | Standing overhead press; ribs down, biceps by ears. | Upper | Front | ✓ |
| Side Lunge (Left) | LungeSideLeft | Step left into lateral lunge; sit back into hip, keep trail leg straight. | Lower | Front | ✓ |
| Side Lunge (Right) | LungeSideRight | Step right into lateral lunge; sit back into hip, keep trail leg straight. | Lower | Front | ✓ |
| Skater Hops | SkaterHops | Lateral bounds with soft landings; trailing leg crosses behind. | Lower | Front | ✓ |
| Ski Jumps | SkiJumps | Feet together side-to-side jumps; quick rebounds. | Lower | Front | ✓ |
| Standing Alternate Toe Touch | StandingAlternateToeTouch | Alternating opposite hand-to-foot touches with slight twist. | Back, Lower | Front | ✓ |
| Standing Bicycle Crunches | StandingBicycleCrunches | Alternating knee-to-opposite-elbow while standing. | Back, Lower | Front | ⏳ |
| Standing Oblique Crunches | StandingObliqueCrunches | Drive knee to same-side elbow; avoid trunk collapse. | Lower, Abs | Front | ✓ |
| Squat And Step | SquatAndStep | Squat then step laterally, alternating sides. | Lower | Front | ⏳ |
| Quad Thoratic Rotation | QuadThoraticRotation | Quadruped thoracic rotation: hand behind head, rotate elbow to ceiling. | Back, Upper | Side | ⏳ |
| Sumo Squat | SquatSumo | Wide-stance squat with toes slightly out; upright torso. | Lower | Front | ✓ |

---

## Static / Isometric

| Movement | SDK String | Description | Body Zone | Preferred View | Video |
| --- | --- | --- | --- | --- | --- |
| High Plank Hold | PlankHighStatic | Top of push-up position; straight line ear-to-ankle. | Abs, Upper, Lower | Front | ✓ |
| Lunge Regular Static (left) | LungeRegularStaticLeft | Isometric forward lunge hold—left leg forward. | Lower | Side | ✓ |
| Lunge Regular Static (right) | LungeRegularStaticRight | Isometric forward lunge hold—right leg forward. | Lower | Side | ✓ |
| LungeSideStatic | LungeSideStaticLeft | Static side-lunge hold—left. | Lower | Front | ✓ |
| LungeSideStatic (right) | LungeSideStaticRight | Static side-lunge hold—right. | Lower | Front | ✓ |
| Overhead Squat Hold | SquatRegularOverheadStatic | Isometric squat with arms locked overhead for thoracic/shoulder mobility. | Back, Upper, Lower | Front | ✓ |
| Side Plank | PlankSideLowStatic | Forearm side plank; stacked feet/knees, hips high. | Upper, Abs | Side | ✓ |
| Static Air Squat | SquatRegularStatic | Isometric hold at squat depth (~90° knee flexion). | Lower | Front | ✓ |
| Sumo Squat static | SquatSumoStatic | Isometric hold at sumo depth. | Lower | Front | ✓ |
| Tuck Hold | TuckHold | Static tuck/V-sit hold; ribs down, shins parallel to floor. | Abs | Side | ✓ |

---

## MSK & Mobility

| Movement | SDK String | Description | Body Zone | Preferred View | Video |
| --- | --- | --- | --- | --- | --- |
| Ankle Flexion (left) | AnkleMobilityLeft | Ankle dorsiflexion mobility (knee over toes) left side. | Lower (ankle) | Side | ⏳ |
| Ankle Flexion (right) | AnkleMobilityRight | Ankle dorsiflexion mobility (knee over toes) right side. | Lower (ankle) | Side | ⏳ |
| Hamstring (seated) | HamstringMobility | Seated forward fold assessing hamstring flexibility. | Posterior chain | Side | ✓ |
| Hip external rotation (glutes) | HipExternalRotationGlutesMobility | Seated/figure-four style external rotation mobility. | Hips/Groin | Side | ⏳ |
| Hip Flexion | HipFlexionMobility | Active hip flexion range test. | Hips/Groin | Side | ⏳ |
| Hip internal rotation | HipInternalRotationMobility | Seated/internal rotation mobility test. | Hips/Groin | Side | ⏳ |
| Inner thigh (butterfly sit) | InnerThighMobility | Seated butterfly stretch assessing groin flexibility. | Hips/Groin | Side | ⏳ |
| Jefferson Curl | JeffersonCurlRight | Slow segmental spinal flexion; light weight only; control throughout. | Back, Hamstrings | Side | ✓ |
| Shoulder Overhead | OverheadMobility | Active shoulder flexion overhead; keep ribs down. | Upper | Side | ⏳ |
| Single leg Knee Raise | StandingKneeRaiseLeft | Standing hip flexion to ~90° on left leg support. | Hips/Groin | Front | ✓ |
| Single leg Knee Raise (right) | StandingKneeRaiseRight | Standing hip flexion to ~90° on right leg support. | Hips/Groin | Front | ✓ |
| Standing Side Bend | StandingSideBendLeft | Standing lateral trunk flexion to the left/right side. | Abs, Obliques | Front | ✓ |
| Standing Side Bend (right) | StandingSideBendRight | Standing lateral trunk flexion to the right. | Abs, Obliques | Front | ✓ |

---

## Utility / Meta Detectors

| Movement | SDK String | Description | Body Zone | Preferred View | Video |
| --- | --- | --- | --- | --- | --- |
| Rest Period | Rest | Represents rest time between active exercises; allows structured workout pacing and recovery tracking. | — | — | — |
| Cooldown | Cooldown | Marks post-session cooldown phase or low-intensity transition; helps produce accurate session summaries. | — | — | — |

---
