#  Crowd and traffic tracking using remote sensing and its public safety applications
## Plz use this benevolently 

![gif](https://media.giphy.com/media/RJbX7sCugWT3A5prZC/giphy.gif)
|:--:|

I do want to preface this as I originally thought that this would be a really interesting topic that could be used to make it easier for first responders and other emergency personnel to safely manage public evacuations. The more I read into the subject though, the more I realized that it could also be easily used to track people and maybe infringe on our privacy. So hopefully this technology won’t ever be used for nefarious purposes!

Drones and other UAV technology can be used to track crowd density. A Space-time multi-scale attention network (STANet) can use this technology to solve density map estimation, localization, and tracking. Drone tracking and STANet can be used to accurately track crowd density and movement and it can be applied to public safety to help prevent potentially deadly stampedes. One important aspect of STANet is using spatio-temporal information to improve counting accuracy.

![image](https://user-images.githubusercontent.com/127619036/235059984-77392fc8-631a-4029-9951-b2cf108c9892.png)
|:--:|
| *Some annotated example frames in the DroneCrowd dataset. Different color indicates different object instance and the corresponding trajectory. The video-level attributes are presented on the top-left corner in each video frame.* |

![image](https://user-images.githubusercontent.com/127619036/235060082-c731f345-e1e6-41df-b949-68eddb80f830.png)

Similar technology that we see in STANet and crowd tracking drones can also be used to extract vehicle trajectories that can then be used to advance autonomous vehicle safety, proactive traffic safety, as well as other traffic safety applications. The advantage to using drones instead of sensors mounted on vehicles or roadside cameras is that drones have a wider detection area and are better at preserving vehicle shapes. The work that CitySim is doing is to provide accurate vehicle trajectories that contain a wider trajectory ranger. This allows for more critical safety events to be captured and for better vehicle geometric representation. Then it can be used to create a digital twin that can be used to better research traffic safety events such as intersection conflicts. One of the interesting aspects of the CitySim research is their use of more accurate bounding boxes to help ensure that the vehicle does not appear larger than it is when going around curves.

![image](https://user-images.githubusercontent.com/127619036/235060180-5257c33d-dfd5-4fba-9b8f-2a36334c6a32.png)

![image](https://user-images.githubusercontent.com/127619036/235060239-edb4e267-1ebc-4d16-ab63-0b91e5a1048e.png)

![image](https://user-images.githubusercontent.com/127619036/235060351-97811407-95ea-43b7-bdb2-1ced95a00653.png)

![image](https://user-images.githubusercontent.com/127619036/235060433-e92b270b-421c-4f1f-9817-1ad0114727fc.png)

![image](https://user-images.githubusercontent.com/127619036/235060579-de55e7fd-6521-4ee8-93f2-66b052eaf438.png)

Evacuation mapping and optimization can use a combination of crowd and traffic tracking to make sure that when disaster strikes populations can be safely evacuated and avoid dangerous bottlenecks that impede evacuation. Simulation of Urban Mobility can create traffic simulations that can help aid in planning safe and effective evacuations. Currently if a vehicle has a deterministic fixed route, it will get stuck if there is a blocked exit and cannot safely evacuate. A vehicle with automatic rerouting would be able to react to this issue and still safely evacuate. In most scenarios it is human behavior that causes evacuation methods to fail, which is why using SUMO and other remote sensing mapping technologies proves to be more effective. 

![image](https://user-images.githubusercontent.com/127619036/235060675-483f1f45-db00-4b53-8879-4b32eb4dd42f.png)

# Sources
[Li, Jinhua, et al. "Improving the Accuracy and Efficiency of Deep Learning-Based Land Cover Mapping via Active Learning and Dynamic Label Selection." arXiv preprint arXiv:1912.01811v1 (2019).](https://arxiv.org/pdf/1912.01811v1.pdf)


[Zhang, Qichao, et al. "Modeling the Impact of COVID-19 Vaccines on Future Hospitalizations and Deaths in the United States." arXiv preprint arXiv:2208.11036 (2022).](https://arxiv.org/ftp/arxiv/papers/2208/2208.11036.pdf)


[Hénaff, Olivier J. "Data-Driven Methods for Structured High-Dimensional Econometric Models." arXiv preprint arXiv:2002.06198v4 (2021).](https://arxiv.org/pdf/2002.06198v4.pdf)
