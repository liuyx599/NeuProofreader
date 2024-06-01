# NeuProofreader( ICME DEMO TRACK 2024)
NeuProofreader: An Interactive Proofreading System with Suggesstive Prompts for Connectomics


# Release status
the Client and Server: 
BaiDuYun Link： [https://pan.baidu.com/s/1itgXNOML46tkrIk4DY02ug?pwd=divb](https://pan.baidu.com/s/1itgXNOML46tkrIk4DY02ug?pwd=divb)   Code：divb

The client and server are packaged executables, unzip them and run `.exe` directly.
The server side is the proofreading status server, whose repository is: the status saving module [https://github.com/liuyx599/NeuroglancerJsonServer-packup](https://github.com/liuyx599/NeuroglancerJsonServer-packup)

Key shortcuts for NeuProofreader:
| Keyboard shortcuts | Functionalities                                              |
|--------------------|-------------------------------------------------------------|
| Tab                | Display algorithmic prompt messages.                        |
| ~                  | Display candidate fragments exceed a threshold merge score.  |
| J                  | Jump to the truncation point between a candidate and the selected segment.  |
| Q                  | Jump to the truncation point between a candidate fragment in the query box. |
| M                  | Merge individual fragments.                                 |
| C                  | Split individual fragments.                                 |
| T                  | Keep the candidate displayed with the highest merge score.  |
| Ctrl+T             | Directly displaying the top 5 candidates with the highest merge scores. |
| Ctrl+M             | Merge all the displayed fragments.                          |
| Ctrl+C             | Split all the displayed fragments.                          |
| Shift+C            | Bulk splitting a collection of fragments from a specific neuron. |
| Shift+S            | Toggle the colors for pre- and post-merging rendering.      |
| Backspace          | Clean algorithmic prompt messages.                          |


# References
```
@inproceedings{chen2024learning,
      title={NeuProofreader: An Interactive Proofreading System with Suggesstive Prompts for Connectomics}, 
      author={Yixiong Liu, Qihua Chen, Xuejin Chen},
      year={2024},
      booktitle={2024 IEEE International Conference on Multimedia and Expo Workshops},
}

@inproceedings{chen2024learning,
      title={Learning Multimodal Volumetric Features for Large-Scale Neuron Tracing}, 
      author={Qihua Chen and Xuejin Chen and Chenxuan Wang and Yixiong Liu and Zhiwei Xiong and Feng Wu},
      year={2024},
      booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
}


@misc{maitin-shepard2021googleneuroglancer,
  author       = {Maitin-Shepard, Jeremy and Baden, Aaron and Silversmith, William and Perlman, Eric and Collman, Forrest and Blakely, Tim and Funke, Jan and Jordan, Christina and Falk, Ben and Kemnitz, Nick and Tingzhao and Roat, Christine and Castro, Mark and Jagan-Nathan, Santhosh and Moenigin and Clements, John and Hoag, Andrew and Katz, Boris and Parsons, Drew and Wu, Jinyang and Kamentsky, Lee and Chervakov, Pavel and Hubbard, Paul and Berg, Sabrina and Hoffer, Jeremy and Halageri, Ankur and Machacek, Christopher and Mader, Kevin and Roeder, Leslie and Li, Peter H.},
  title        = {{google/neuroglancer}},
  month        = oct,
  year         = 2021,
  publisher    = {Zenodo},
  version      = {2.0.0},
  url          = {https://zenodo.org/record/5573294}
}
```
