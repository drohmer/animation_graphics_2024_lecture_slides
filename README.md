# Animation in Graphics 2024 training days - course slides

Source code for the slides used during the (https://imagecomputing.net/course/2024_gdr_igrv/)[Training Days of Animation in Graphics 2024].



## Download

```
git clone --recursive https://github.com/drohmer/animation_graphics_2024_lecture_slides.git
```

## Run

```
python generate.py [--pdf] [--all] [--videos]
```


* --pdf: Generate pdf output as well as one image per slide.

* --all: Generate all directories in src/. Otherwise generates only the directory set in the variable compile_dirs (defined in generate.py).

* --videos: Compute cached videos in multiple formats (.mp4, .webm) for maximal compatibility on various systems (can take a while).



_Slides are generated by default in \_site/ directory_


<p align="center"> 
<img align="center" src="assets/slide_example.gif" width="60%">
</p>



## Licence

The code of the slides are provided as open-source under the MIT licence. 

Note that some images and videos used for illustrations may be under copyright, their use is only intended for teaching purpose.