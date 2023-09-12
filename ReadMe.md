### Participants

We gathered data from 42 individuals, 34 male and 8 female, with the male skew likely due to our host university's gender ratio. 34 volunteers are in the 18-24 age category, with 3 volunteers in the 24-60 age range and the remaining 5 volunteers in the 65-90 age category. Volunteers in the 65-90 age category are hospital patients who volunteered to ride the scooter and allow testing of whether our model, trained primarily on younger volunteers, can also work well on typical mobility scooter users.

### Tasks Performed

To collect posture data from mobility scooter participants in dynamic situations, we devised four tasks that participants should engage in. 

1. Participants would ride the scooter along a designated track that includes gradual inclines, descents, gradual and sharp left and right turns, and backward movements. This track took most participants approximately 4 minutes.
2. The next task was intentionally less rigid to encourage realistic and individualistic usage of the scooter. We asked participants to drive for 5 minutes in any direction on the designated paths, which intersected several times to allow riders to choose their own destination and route.
3. Similarly to the previous tasks, we next asked participants to ride off-road and on grassy and hilly terrain for 5 minutes for data in a dynamic environment with a less steady camera.
4. Our final task has users ride on a small track and perform several bouts of acceleration and sudden stopping. This task allows us to gather frequent stopping and acceleration data, which is largely not present in the other tasks. 

The majority of volunteers completed all the above tasks, although several completed only tasks 1 and 2, and our hospital patients engaged in a longer routine that extended the above tasks. Most individuals spent in the range of 15-20 minutes completing the 4 tasks, with the hospital patients spending 30-40 minutes for their extended tasks. 

### Data Collection Methods

During these tasks, the subject's torso is recorded by two sensor arrays, one of which contains a wide-angle camera. We then process the video footage from the wide-angle camera to extract several key points. We use Google MediaPipe for the data extraction.


### Data Format

(x_i,y_i, z_i) on row k correspond to the 3D data for joint i at frame j.

The index to joint pairing is as follows:
0 - Nose,  1 - Left Shoulder,  2 - Right Shoulder, 3 - Left Elbow, 4 - Right Elbow, 5 - Left Wrist, 6 - Right Wrist, 7 - Left Hip, 8 - Right Hip

### Associated Data
Form: [File Name]: [Age], [Biological Gender], [Height], [Weight], [Medical Condition], [Impairment]

- *Volunteer 0:* 87, F, 5ft 8in, 200, Neuropathy, Neck and Trunk
- *Volunteer 1:* 53, M, 6ft 1in, 172, Brain Injury, Lower extr.
- *Volunteer 2:* 85, F, 5ft 6in, 230, Sciatica, Left lower extr.
- *Volunteer 3:* 90, F, 5ft 7in, 156, Arthritis, Both hips
- *Volunteer 4:* 62, M, 5ft 7in, 180, Back, Shoulder and Hips
- *Volunteer 5:* 24, F, *, *
- **Volunteer 6:* 21, M, *, *
- **Volunteer 7:* 18-25, M, *, *
- **Volunteer 8:* 18-25, M, *, *
- **Volunteer 9:* 19, M, 5ft 10in, 155
- **Volunteer 10:* 18-25, M, *, *
- **Volunteer 11:* 21, M, *, *
- **Volunteer 12:* 20, M, *, *
- **Volunteer 13:* 19, M, *, *
- **Volunteer 14:* 26-60, F, *, *
- **Volunteer 15:* 46, M, *, *
- **Volunteer 16:* 20, M, 5ft 8in, 140
- **Volunteer 17:* 20, F, *, *
- **Volunteer 18:* 23, M, *, *
- **Volunteer 19:* 21, M, *, *
- **Volunteer 20:* 30, F, *, *
- **Volunteer 21:* 24, M, *, *
- **Volunteer 22:* 18, M, *, *
- **Volunteer 23:* 20, M, *, *
- **Volunteer 24:* 24, M, *, *
- **Volunteer 25:* 18, M, 6ft 0in, 280
- **Volunteer 26:* 24, M, *, *
- **Volunteer 27:* 19, M, *, *
- **Volunteer 28:* 18, M, *, *
- **Volunteer 29:* 20, F, *, *
- **Volunteer 30:* 20, M, 5ft 10in, 220
- **Volunteer 31:* 20, M, *, *
- **Volunteer 32:* 25, M, *, *
- **Volunteer 33:* 19, M, *, *
- **Volunteer 34:* 18, M, *, *
- **Volunteer 35:* 18-25, F, *, *
- **Volunteer 36:* 18-25, M, *, *
- **Volunteer 37:* 20, M, 5ft 10in, 185
