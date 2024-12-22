 Scan relevant files in the specified directory

1.can open Live2d v2.1 file  
	{"*.moc",  "*.moc.bytes"}		
	Future versions{ "*.moc3", "*.moc3.bytes" }
2.can open Spine 4.2 4.1 4.0 3. 3.7 3.6 3.5 3.4 3.0 2.1 file
    	 (json format file binary format file)
	{ "*.skel", "*.skel.bytes", "*.json" }
	{ "*.atlas.prefab","*.prefab"  }

3.can open Lpk wpk file
       { "*.lpk", "*.wpk" }

4.slice texture,
    when	the original photoshop file is missing,
    two steps create  *.psd file(    two steps  maybe Future versions)
      First, slice texture,keep rotating ,posion to *.pngs files,
    scecond ,photoshop import these *.pngs files  to  one  *.psd file.

5.texture  to PMA (PremultiplyAlpha),
  PMA  (PremultiplyAlpha) to Straight Alpha
  resize texture
