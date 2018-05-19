.. highlight:: lua

Changelog
###########################################

| v3.4 Math kurisu
| april 28th 2018

News Defauls Functions: (46)
----------------------------
| **table library**
| 	table.combine( Table, n_combinations )
| 	table.set( color_masktable )
| 	table.delete( Table, ... )
| 	table.permute( Table )
| 	table.ipol( Values, Size )
| 
| **string library**
| 	string.count( String, Capture )
| 	string.toval( String )
| 	string.i( String )
| 	string.change( String, Capture, NoDelete, NoCapture )
| 	string.cap( String, Capture, Extra_Capture, Filter )
| 
| **math library**
| 	math.format( String, val )
| 	math.format2( String, val )
| 	math.circle( Shape )
| 	math.rotate( p, axis, angle )
| 
| **tag library**
| 	tag.default2( String )
| 	tag.Pclip( size_clip, left_cx, top_cy, width_clip, height_clip )
| 	tag.Piclip( size_clip, left_cx, top_cy, width_clip, height_clip )
| 	tag.movePclip( size_clip, left_cx, top_cy, width_clip, height_clip )
| 	tag.movePiclip( size_clip, left_cx, top_cy, width_clip, height_clip )
| 	tag.cyclic( Dur, Dur_tr, Delay, Fad_i, Fad_f, tags_ini, tags_fin )
| 	tag.filter( String, Tag, Filter )
| 
| **color library**
| 	color.vector( color1, color2 )
| 	color.moduler( color1_or_table, color2_or_table )
| 
| **alpha library**
| 	alpha.moduler( alpha1_or_table, alpha2_or_table )		
| 	alpha.ipol( ... )
| 	alpha.loop( ... )
| 
| **shape library**
| 	shape.to_bezier( Shape )
| 	shape.lineclip( Mode, Dur, Ini )
| 	shape.setclip( Set_clips, Set_tagfx, Indx_line )
| 	shape.multi6( Size, Bord, Part )
| 	shape.multi7( Part, Radius )
| 	shape.multi8( Shape, Size_ini, Size_fin, Loop )
| 	shape.multi9( Shape, Loop, Tags )
| 	shape.fxline( P1, P2, Radius )
| 	shape.fxcircle( Shape )
| 	shape.trim( Shape, Lines, Mark, Ratio )
| 	shape.reduce( Shape )
| 	shape.inclip( Tags )
| 	shape.allin( Shape, Tags )
| 	shape.fusion( Shapes, Tags )
| 
| **text library**
| 	text.rand( Text_ran, num_tran, dur_tran, extra_tags, table_rand, text_all )
| 	text.inclip( Text )
| 	text.outclip( Text )
| 
| **image library**
| 	image.data( bmp_image, Return )
| 	image.to_pixels( bmp_image, Size )
| 
| **effector library**
| 	effector.keeptags( template_type, keeptags_type )
| 
| 

News Defaults fx: (1502)
------------------------
| **lead-in FX List**
| 	ABC Create New fx
| 	Agitation Char I buttline
| 	Agitation Char I inverse
| 	Agitation Char I midline
| 	Animated Clip I buttline
| 	Animated Clip I inverse
| 	Animated Clip I midline
| 	Animated Clip II fry buttline
| 	Animated Clip II fry inverse
| 	Animated Clip II fry midline
| 	Animated Clip III Top buttline
| 	Animated Clip III Top inverse
| 	Animated Clip III Top midline
| 	Animated Clip IV Bottom buttline
| 	Animated Clip IV Bottom inverse
| 	Animated Clip IV Bottom midline
| 	Animated Clip V Alternate buttline
| 	Animated Clip V Alternate inverse
| 	Animated Clip V Alternate midline
| 	Animated Clip VI tags functions buttline
| 	Animated Clip VI tags functions inverse
| 	Animated Clip VI tags functions midline
| 	Animated Clip VII tags functions oscill buttline
| 	Animated Clip VII tags functions oscill inverse
| 	Animated Clip VII tags functions oscill midline
| 	Animated Clip VIII loop 4 buttline
| 	Animated Clip VIII loop 4 inverse
| 	Animated Clip VIII loop 4 midline
| 	Animated Clip IX loop 4 faxy buttline
| 	Animated Clip IX loop 4 faxy inverse
| 	Animated Clip IX loop 4 faxy midline
| 	Animated Clip X loop 4 tags functions buttline
| 	Animated Clip X loop 4 tags functions inverse
| 	Animated Clip X loop 4 tags functions midline
| 	Asault buttline
| 	Asault inverse
| 	Asault midline
| 	Asault II
| 	Asault II leadin
| 	Asault II buttline
| 	Asault II inverse
| 	Asault II midline
| 	Asault Line I Bottom buttline
| 	Asault Line I Bottom inverse
| 	Asault Line I Bottom midline
| 	Asault Line II Top
| 	Asault Line II Top leadin
| 	Asault Line II Top buttline
| 	Asault Line II Top inverse
| 	Asault Line II Top midline
| 	Asault Line III BT
| 	Asault Line III BT leadin
| 	Asault Line III BT buttline
| 	Asault Line III BT inverse
| 	Asault Line III BT midline
| 	Auxiliar Bord Shine I buttline
| 	Auxiliar Bord Shine I inverse
| 	Auxiliar Bord Shine I midline
| 	Auxiliar MultiClip I H buttline
| 	Auxiliar MultiClip I H inverse
| 	Auxiliar MultiClip I H midline
| 	Auxiliar MultiClip II V
| 	Auxiliar MultiClip II V buttline
| 	Auxiliar MultiClip II V inverse
| 	Auxiliar MultiClip II V midline
| 	Auxiliar Spark Shine I buttline
| 	Auxiliar Spark Shine I inverse
| 	Auxiliar Spark Shine I midline
| 	Auxiliar Spark Shine II
| 	Auxiliar Spark Shine II buttline
| 	Auxiliar Spark Shine II inverse
| 	Auxiliar Spark Shine II midline
| 	Auxiliar Spark Shine III buttline
| 	Auxiliar Spark Shine III inverse
| 	Auxiliar Spark Shine III midline
| 	Auxiliar Spark Shine IV buttline
| 	Auxiliar Spark Shine IV inverse
| 	Auxiliar Spark Shine IV midline
| 	Baker Street I LR buttline
| 	Baker Street I LR inverse
| 	Baker Street I LR midline
| 	Baker Street II RL
| 	Baker Street II RL buttline
| 	Baker Street II RL inverse
| 	Baker Street II RL midline
| 	Baker Street III RLR Alternate
| 	Baker Street III RLR Alternate buttline
| 	Baker Street III RLR Alternate inverse
| 	Baker Street III RLR Alternate midline
| 	Baker Street IV TB
| 	Baker Street IV TB buttline
| 	Baker Street IV TB inverse
| 	Baker Street IV TB midline
| 	Baker Street V BT
| 	Baker Street V BT buttline
| 	Baker Street V BT inverse
| 	Baker Street V BT midline
| 	Baker Street VI TBT Alternate
| 	Baker Street VI TBT Alternate buttline
| 	Baker Street VI TBT Alternate inverse
| 	Baker Street VI TBT Alternate midline
| 	Bord to Pixels Shine I buttline
| 	Bord to Pixels Shine I inverse
| 	Bord to Pixels Shine I midline
| 	Bord to Pixels Shine II buttline
| 	Bord to Pixels Shine II inverse
| 	Bord to Pixels Shine II midline
| 	Bord to Pixels Shine III buttline
| 	Bord to Pixels Shine III inverse
| 	Bord to Pixels Shine III midline
| 	Bord to Pixels Shine IV buttline
| 	Bord to Pixels Shine IV inverse
| 	Bord to Pixels Shine IV midline
| 	Bord to Pixels Shine V buttline
| 	Bord to Pixels Shine V inverse
| 	Bord to Pixels Shine V midline
| 	Bord to Pixels Shine VI buttline
| 	Bord to Pixels Shine VI inverse
| 	Bord to Pixels Shine VI midline
| 	Bord to Pixels Shine VII buttline
| 	Bord to Pixels Shine VII inverse
| 	Bord to Pixels Shine VII midline
| 	Char Clip 4 I
| 	Char Clip 4 I buttline
| 	Char Clip 4 I inverse
| 	Char Clip 4 I midline
| 	Char Clip 4 II
| 	Char Clip 4 II buttline
| 	Char Clip 4 II inverse
| 	Char Clip 4 II midline
| 	Char Random I buttline
| 	Char Random I inverse
| 	Char Random I midline
| 	Char Random II numbers buttline
| 	Char Random II numbers inverse
| 	Char Random II numbers midline
| 	Char Random III binary
| 	Char Random III binary buttline
| 	Char Random III binary inverse
| 	Char Random III binary midline
| 	Char Random IV Ascend
| 	Char Random IV Ascend buttline
| 	Char Random IV Ascend inverse
| 	Char Random IV Ascend midline
| 	Char Random V Ascend numbers
| 	Char Random V Ascend numbers buttline
| 	Char Random V Ascend numbers inverse
| 	Char Random V Ascend numbers midline
| 	Char Random VI Ascend binary
| 	Char Random VI Ascend binary buttline
| 	Char Random VI Ascend binary inverse
| 	Char Random VI Ascend binary midline
| 	Char Random VII Descend
| 	Char Random VII Descend buttline
| 	Char Random VII Descend inverse
| 	Char Random VII Descend midline
| 	Char Random VIII Descend numbers
| 	Char Random VIII Descend numbers buttline
| 	Char Random VIII Descend numbers inverse
| 	Char Random VIII Descend numbers midline
| 	Char Random IX Descend binary
| 	Char Random IX Descend binary buttline
| 	Char Random IX Descend binary inverse
| 	Char Random IX Descend binary midline
| 	Char Random X ADA Alternate
| 	Char Random X ADA Alternate buttline
| 	Char Random X ADA Alternate inverse
| 	Char Random X ADA Alternate midline
| 	Char Random XI ADA Alternate numbers
| 	Char Random XI ADA Alternate numbers buttline
| 	Char Random XI ADA Alternate numbers inverse
| 	Char Random XI ADA Alternate numbers midline
| 	Char Random XII ADA Alternate binary
| 	Char Random XII ADA Alternate binary buttline
| 	Char Random XII ADA Alternate binary inverse
| 	Char Random XII ADA Alternate binary midline
| 	Char Random XIII ADA rand
| 	Char Random XIII ADA rand buttline
| 	Char Random XIII ADA rand inverse
| 	Char Random XIII ADA rand midline
| 	Char Random XIV ADA rand numbers
| 	Char Random XIV ADA rand numbers buttline
| 	Char Random XIV ADA rand numbers inverse
| 	Char Random XIV ADA rand numbers midline
| 	Char Random XV ADA rand binary
| 	Char Random XV ADA rand binary buttline
| 	Char Random XV ADA rand binary inverse
| 	Char Random XV ADA rand binary midline
| 	Char Random XVI LR
| 	Char Random XVI LR buttline
| 	Char Random XVI LR inverse
| 	Char Random XVI LR midline
| 	Char Random XVII RL
| 	Char Random XVII RL buttline
| 	Char Random XVII RL inverse
| 	Char Random XVII RL midline
| 	Char Random XVIII line numbers
| 	Char Random XVIII line binary
| 	Char Random XIX line Ascend
| 	Char Random XIX line Ascend numbers
| 	Char Random XIX line Ascend binary
| 	Char Random XX line Descend
| 	Char Random XX line Descend numbers
| 	Char Random XX line Descend binary
| 	Char Randon XXI line ADA Alternate
| 	Char Randon XXI line ADA Alternate numbers
| 	Char Randon XXI line ADA Alternate binary
| 	Char Randon XXII line ADA rand
| 	Char Randon XXII line ADA rand numbers
| 	Char Randon XXII line ADA rand binary
| 	Char Under Sea I buttline
| 	Char Under Sea I inverse
| 	Char Under Sea I midline
| 	Chess Multi Color buttline
| 	Chess Multi Color inverse
| 	Chess Multi Color midline
| 	Clip Curves I buttline
| 	Clip Curves I inverse
| 	Clip Curves I midline
| 	Clips Rand I frxyz
| 	Clips Rand I frxyz buttline
| 	Clips Rand I frxyz inverse
| 	Clips Rand I frxyz midline
| 	Clips Rand II Colors
| 	Clips Rand II Colors buttline
| 	Clips Rand II Colors inverse
| 	Clips Rand II Colors midline
| 	Clip Triangles I buttline
| 	Clip Triangles I inverse
| 	Clip Triangles I midline
| 	Crazy Oscill I buttline
| 	Crazy Oscill I inverse
| 	Crazy Oscill I midline
| 	Curve Line I buttline
| 	Curve Line I inverse
| 	Curve Line I midline
| 	Deformed Zoom I buttline
| 	Deformed Zoom I inverse
| 	Deformed Zoom I midline
| 	Deformed Zoom I Line
| 	Deformed Zoom II Ascend
| 	Deformed Zoom II Ascend buttline
| 	Deformed Zoom II Ascend inverse
| 	Deformed Zoom II Ascend midline
| 	Deformed Zoom III Descend
| 	Deformed Zoom III Descend buttline
| 	Deformed Zoom III Descend inverse
| 	Deformed Zoom III Descend midline
| 	Deformed Zoom IV ADA Alternate
| 	Deformed Zoom IV ADA Alternate buttline
| 	Deformed Zoom IV ADA Alternate inverse
| 	Deformed Zoom IV ADA Alternate midline
| 	Deformed Zoom V LR
| 	Deformed Zoom V LR buttline
| 	Deformed Zoom V LR inverse
| 	Deformed Zoom V LR midline
| 	Deformed Zoom VI RL
| 	Deformed Zoom VI RL buttline
| 	Deformed Zoom VI RL inverse
| 	Deformed Zoom VI RL midline
| 	Distort Clip In Line I LR
| 	Emerge Clip III HVH Alternate buttline
| 	Emerge Clip III HVH Alternate inverse
| 	Emerge Clip III HVH Alternate midline
| 	Ghost Shake Syl Multi buttline
| 	Ghost Shake Syl Multi inverse
| 	Ghost Shake Syl Multi midline
| 	Ghost Shake Syl Multi Line
| 	Ghost Shakes Simple buttline
| 	Ghost Shakes Simple inverse
| 	Ghost Shakes Simple midline
| 	Ghost Shakes Simple Line
| 	Hattori Syl Cut I
| 	Hattori Syl Cut I buttline
| 	Hattori Syl Cut I inverse
| 	Hattori Syl Cut I midline
| 	Meave Light I buttline
| 	Meave Light I inverse
| 	Meave Light I midline
| 	Move Char I buttline
| 	Move Char I inverse
| 	Move Char I midline
| 	Move Char II Gyre buttline
| 	Move Char II Gyre inverse
| 	Move Char II Gyre midline
| 	Move Char III Ascend
| 	Move Char III Ascend buttline
| 	Move Char III Ascend inverse
| 	Move Char III Ascend midline
| 	Move Char III Ascend preword
| 	Move Char IV Ascend Multi
| 	Move Char IV Ascend Multi buttline
| 	Move Char IV Ascend Multi inverse
| 	Move Char IV Ascend Multi midline
| 	Move Char IV Ascend Multi preword
| 	Move Char V Descend
| 	Move Char V Descend buttline
| 	Move Char V Descend inverse
| 	Move Char V Descend midline
| 	Move Char V Descend preword
| 	Move Char VI Descend Multi
| 	Move Char VI Descend Multi buttline
| 	Move Char VI Descend Multi inverse
| 	Move Char VI Descend Multi midline
| 	Move Char VI Descend Multi preword
| 	Move Syl from Center Line I inverse
| 	Move Syl from Center Line II
| 	Move Syl from Center Line II inverse
| 	Palpitations Char buttline
| 	Palpitations Char inverse
| 	Palpitations Char midline
| 	Screw Char II move
| 	Screw Char II move buttline
| 	Screw Char II move inverse
| 	Screw Char II move midline
| 	Screw Char III fry
| 	Screw Char III fry buttline
| 	Screw Char III fry inverse
| 	Screw Char III fry midline
| 	Screw Char IV fry move
| 	Screw Char IV fry move buttline
| 	Screw Char IV fry move inverse
| 	Screw Char IV fry move midline
| 	Screw Char V frz
| 	Screw Char V frz buttline
| 	Screw Char V frz inverse
| 	Screw Char V frz midline
| 	Screw Char VI frz move
| 	Screw Char VI frz move buttline
| 	Screw Char VI frz move inverse
| 	Screw Char VI frz move midline
| 	Screw Char VII Rectangle
| 	Screw Char VII Rectangle buttline
| 	Screw Char VII Rectangle inverse
| 	Screw Char VII Rectangle midline
| 	Screw Char VIII Rectangle move
| 	Screw Char VIII Rectangle move buttline
| 	Screw Char VIII Rectangle move inverse
| 	Screw Char VIII Rectangle move midline
| 	Screw Char IX Rectangle fry
| 	Screw Char IX Rectangle fry buttline
| 	Screw Char IX Rectangle fry inverse
| 	Screw Char IX Rectangle fry midline
| 	Screw Char X Rectangle fry move
| 	Screw Char X Rectangle fry move buttline
| 	Screw Char X Rectangle fry move inverse
| 	Screw Char X Rectangle fry move midline
| 	Screw Char XI Rectangle frz
| 	Screw Char XI Rectangle frz buttline
| 	Screw Char XI Rectangle frz inverse
| 	Screw Char XI Rectangle frz midline
| 	Screw Char XII Rectangle frz move
| 	Screw Char XII Rectangle frz move buttline
| 	Screw Char XII Rectangle frz move inverse
| 	Screw Char XII Rectangle frz move midline
| 	Snake Char I buttline
| 	Snake Char I inverse
| 	Snake Char I midline
| 	Snake Char II buttline
| 	Snake Char II inverse
| 	Snake Char II midline
| 	SNSD Oh
| 	SNSD Oh buttline
| 	SNSD Oh inverse
| 	SNSD Oh midline
| 	Spectrum Move Char buttline
| 	Spectrum Move Char inverse
| 	Spectrum Move Char midline
| 	Static Clip I Ascend buttline
| 	Static Clip I Ascend inverse
| 	Static Clip I Ascend midline
| 	Static Clip II Descend buttline
| 	Static Clip II Descend inverse
| 	Static Clip II Descend midline
| 	Static Clip III ADA Alternate buttline
| 	Static Clip III ADA Alternate inverse
| 	Static Clip III ADA Alternate midline
| 	Static Clip IV LR buttline
| 	Static Clip IV LR inverse
| 	Static Clip IV LR midline
| 	Static Clip V RL buttline
| 	Static Clip V RL inverse
| 	Static Clip V RL midline
| 	Static Clip VI LRL Alternate buttline
| 	Static Clip VI LRL Alternate inverse
| 	Static Clip VI LRL Alternate midline
| 	Static Clip VII LTRB Alternate
| 	Static Clip VII LTRB Alternate buttline
| 	Static Clip VII LTRB Alternate inverse
| 	Static Clip VII LTRB Alternate midline
| 	Static Clip VIII Horizontal Multi I
| 	Static Clip VIII Horizontal Multi I buttline
| 	Static Clip VIII Horizontal Multi I inverse
| 	Static Clip VIII Horizontal Multi I midline
| 	Static Clip IX Vertical Multi I buttline
| 	Static Clip IX Vertical Multi I inverse
| 	Static Clip IX Vertical Multi I midline
| 	Stela Move I LR buttline
| 	Stela Move I LR inverse
| 	Stela Move I LR midline
| 	Stela Move II RL
| 	Stela Move II RL buttline
| 	Stela Move II RL inverse
| 	Stela Move II RL midline
| 	Stela Move III BT
| 	Stela Move III BT buttline
| 	Stela Move III BT inverse
| 	Stela Move III BT midline
| 	Stela Move IV TB
| 	Stela Move IV TB buttline
| 	Stela Move IV TB inverse
| 	Stela Move IV TB midline
| 	Stela Move V BTB Alternate
| 	Stela Move V BTB Alternate buttline
| 	Stela Move V BTB Alternate inverse
| 	Stela Move V BTB Alternate midline
| 	Wavelet Char buttline
| 	Wavelet Char inverse
| 	Wavelet Char midline
| 	
| **hi-light FX List**
| 	ABC Create New fx
| 	Amorphous Syl I MultiColor
| 	Bee V D1
| 	Bee VI D2
| 	Bee VII DA
| 	Bee VIII DD
| 	Char Clip 4 I
| 	Char Clip 4 II
| 	Char Flame I
| 	Clip Rand I oscill faxy
| 	Halo Border Shine IV Horizontal
| 	Halo Border Shine V HV
| 	Persistence Of Color I
| 	Shine Twist I
| 	Shine Twist II
| 	Shine Twist III Alternate
| 	
| **lead-out FX List**
| 	ABC Create New fx
| 	Agitation Char I
| 	Agitation Char I buttline
| 	Agitation Char I inverse
| 	Agitation Char I midline
| 	Animated Clip I buttline
| 	Animated Clip I inverse
| 	Animated Clip I midline
| 	Animated Clip II fry buttline
| 	Animated Clip II fry inverse
| 	Animated Clip II fry midline
| 	Animated Clip III Top buttline
| 	Animated Clip III Top inverse
| 	Animated Clip III Top midline
| 	Animated Clip IV Bottom buttline
| 	Animated Clip IV Bottom inverse
| 	Animated Clip IV Bottom midline
| 	Animated Clip V Alternate buttline
| 	Animated Clip V Alternate inverse
| 	Animated Clip V Alternate midline
| 	Animated Clip VI tags functions buttline
| 	Animated Clip VI tags functions inverse
| 	Animated Clip VI tags functions midline
| 	Animated Clip VII tags functions oscill buttline
| 	Animated Clip VII tags functions oscill inverse
| 	Animated Clip VII tags functions oscill midline
| 	Animated Clip VIII loop 4 buttline
| 	Animated Clip VIII loop 4 inverse
| 	Animated Clip VIII loop 4 midline
| 	Animated Clip IX loop 4 faxy buttline
| 	Animated Clip IX loop 4 faxy inverse
| 	Animated Clip IX loop 4 faxy midline
| 	Animated Clip X loop 4 tags functions buttline
| 	Animated Clip X loop 4 tags functions inverse
| 	Animated Clip X loop 4 tags functions midline
| 	Asault leadout
| 	Asault buttline
| 	Asault inverse
| 	Asault midline
| 	Asault II
| 	Asault II leadout
| 	Asault II buttline
| 	Asault II inverse
| 	Asault II midline
| 	Asault Line I Bottom leadout
| 	Asault Line I Bottom buttline
| 	Asault Line I Bottom inverse
| 	Asault Line I Bottom midline
| 	Asault Line II Top
| 	Asault Line II Top leadout
| 	Asault Line II Top buttline
| 	Asault Line II Top inverse
| 	Asault Line II Top midline
| 	Asault Line III BT
| 	Asault Line III BT leadout
| 	Asault Line III BT buttline
| 	Asault Line III BT inverse
| 	Asault Line III BT midline
| 	Auxiliar Bord Shine I
| 	Auxiliar Bord Shine I buttline
| 	Auxiliar Bord Shine I inverse
| 	Auxiliar Bord Shine I midline
| 	Auxiliar MultiClip I H
| 	Auxiliar MultiClip I H buttline
| 	Auxiliar MultiClip I H inverse
| 	Auxiliar MultiClip I H midline
| 	Auxiliar MultiClip II V
| 	Auxiliar MultiClip II V buttline
| 	Auxiliar MultiClip II V inverse
| 	Auxiliar MultiClip II V midline
| 	Auxiliar Spark Shine I
| 	Auxiliar Spark Shine I buttline
| 	Auxiliar Spark Shine I inverse
| 	Auxiliar Spark Shine I midline
| 	Auxiliar Spark Shine II
| 	Auxiliar Spark Shine II buttline
| 	Auxiliar Spark Shine II inverse
| 	Auxiliar Spark Shine II midline
| 	Auxiliar Spark Shine III
| 	Auxiliar Spark Shine III buttline
| 	Auxiliar Spark Shine III inverse
| 	Auxiliar Spark Shine III midline
| 	Auxiliar Spark Shine IV
| 	Auxiliar Spark Shine IV buttline
| 	Auxiliar Spark Shine IV inverse
| 	Auxiliar Spark Shine IV midline
| 	Baker Street I LR
| 	Baker Street I LR buttline
| 	Baker Street I LR inverse
| 	Baker Street I LR midline
| 	Baker Street II RL
| 	Baker Street II RL buttline
| 	Baker Street II RL inverse
| 	Baker Street II RL midline
| 	Baker Street III RLR Alternate
| 	Baker Street III RLR Alternate buttline
| 	Baker Street III RLR Alternate inverse
| 	Baker Street III RLR Alternate midline
| 	Baker Street IV TB
| 	Baker Street IV TB buttline
| 	Baker Street IV TB inverse
| 	Baker Street IV TB midline
| 	Baker Street V BT
| 	Baker Street V BT buttline
| 	Baker Street V BT inverse
| 	Baker Street V BT midline
| 	Baker Street VI TBT Alternate
| 	Baker Street VI TBT Alternate buttline
| 	Baker Street VI TBT Alternate inverse
| 	Baker Street VI TBT Alternate midline
| 	Bord to Pixels Shine I buttline
| 	Bord to Pixels Shine I inverse
| 	Bord to Pixels Shine I midline
| 	Bord to Pixels Shine II buttline
| 	Bord to Pixels Shine II inverse
| 	Bord to Pixels Shine II midline
| 	Bord to Pixels Shine III buttline
| 	Bord to Pixels Shine III inverse
| 	Bord to Pixels Shine III midline
| 	Bord to Pixels Shine IV buttline
| 	Bord to Pixels Shine IV inverse
| 	Bord to Pixels Shine IV midline
| 	Bord to Pixels Shine V buttline
| 	Bord to Pixels Shine V inverse
| 	Bord to Pixels Shine V midline
| 	Bord to Pixels Shine VI buttline
| 	Bord to Pixels Shine VI inverse
| 	Bord to Pixels Shine VI midline
| 	Bord to Pixels Shine VII buttline
| 	Bord to Pixels Shine VII inverse
| 	Bord to Pixels Shine VII midline
| 	Char Clip 4 I
| 	Char Clip 4 I buttline
| 	Char Clip 4 I inverse
| 	Char Clip 4 I midline
| 	Char Clip 4 II
| 	Char Clip 4 II buttline
| 	Char Clip 4 II inverse
| 	Char Clip 4 II midline
| 	Char Random I buttline
| 	Char Random I inverse
| 	Char Random I midline
| 	Char Random II numbers buttline
| 	Char Random II numbers inverse
| 	Char Random II numbers midline
| 	Char Random III binary
| 	Char Random III binary buttline
| 	Char Random III binary inverse
| 	Char Random III binary midline
| 	Char Random IV Ascend
| 	Char Random IV Ascend buttline
| 	Char Random IV Ascend inverse
| 	Char Random IV Ascend midline
| 	Char Random V Ascend numbers
| 	Char Random V Ascend numbers buttline
| 	Char Random V Ascend numbers inverse
| 	Char Random V Ascend numbers midline
| 	Char Random VI Ascend binary
| 	Char Random VI Ascend binary buttline
| 	Char Random VI Ascend binary inverse
| 	Char Random VI Ascend binary midline
| 	Char Random VII Descend
| 	Char Random VII Descend buttline
| 	Char Random VII Descend inverse
| 	Char Random VII Descend midline
| 	Char Random VIII Descend numbers
| 	Char Random VIII Descend numbers buttline
| 	Char Random VIII Descend numbers inverse
| 	Char Random VIII Descend numbers midline
| 	Char Random IX Descend binary
| 	Char Random IX Descend binary buttline
| 	Char Random IX Descend binary inverse
| 	Char Random IX Descend binary midline
| 	Char Random X ADA Alternate
| 	Char Random X ADA Alternate buttline
| 	Char Random X ADA Alternate inverse
| 	Char Random X ADA Alternate midline
| 	Char Random XI ADA Alternate numbers
| 	Char Random XI ADA Alternate numbers buttline
| 	Char Random XI ADA Alternate numbers inverse
| 	Char Random XI ADA Alternate numbers midline
| 	Char Random XII ADA Alternate binary
| 	Char Random XII ADA Alternate binary buttline
| 	Char Random XII ADA Alternate binary inverse
| 	Char Random XII ADA Alternate binary midline
| 	Char Random XIII ADA rand
| 	Char Random XIII ADA rand buttline
| 	Char Random XIII ADA rand inverse
| 	Char Random XIII ADA rand midline
| 	Char Random XIV ADA rand numbers
| 	Char Random XIV ADA rand numbers buttline
| 	Char Random XIV ADA rand numbers inverse
| 	Char Random XIV ADA rand numbers midline
| 	Char Random XV ADA rand binary
| 	Char Random XV ADA rand binary buttline
| 	Char Random XV ADA rand binary inverse
| 	Char Random XV ADA rand binary midline
| 	Char Random XVI LR
| 	Char Random XVI LR buttline
| 	Char Random XVI LR inverse
| 	Char Random XVI LR midline
| 	Char Random XVII RL
| 	Char Random XVII RL buttline
| 	Char Random XVII RL inverse
| 	Char Random XVII RL midline
| 	Char Random XVIII line numbers
| 	Char Random XVIII line binary
| 	Char Random XIX line Ascend
| 	Char Random XIX line Ascend numbers
| 	Char Random XIX line Ascend binary
| 	Char Random XX line Descend
| 	Char Random XX line Descend numbers
| 	Char Random XX line Descend binary
| 	Char Randon XXI line ADA Alternate
| 	Char Randon XXI line ADA Alternate numbers
| 	Char Randon XXI line ADA Alternate binary
| 	Char Randon XXII line ADA rand
| 	Char Randon XXII line ADA rand numbers
| 	Char Randon XXII line ADA rand binary
| 	Chess Multi Color
| 	Chess Multi Color buttline
| 	Chess Multi Color inverse
| 	Chess Multi Color midline
| 	Clip Curves I
| 	Clip Curves I buttline
| 	Clip Curves I inverse
| 	Clip Curves I midline
| 	Clip Curves II Line
| 	Clips Rand I frxyz
| 	Clips Rand I frxyz buttline
| 	Clips Rand I frxyz inverse
| 	Clips Rand I frxyz midline
| 	Clips Rand II Colors
| 	Clips Rand II Colors buttline
| 	Clips Rand II Colors inverse
| 	Clips Rand II Colors midline
| 	Clip Triangles I
| 	Clip Triangles I buttline
| 	Clip Triangles I inverse
| 	Clip Triangles I midline
| 	Clip Triangles II Line
| 	Crazy Oscill I
| 	Crazy Oscill I buttline
| 	Crazy Oscill I inverse
| 	Crazy Oscill I midline
| 	Curve Line I
| 	Curve Line I buttline
| 	Curve Line I inverse
| 	Curve Line I midline
| 	Deformed Zoom I
| 	Deformed Zoom I buttline
| 	Deformed Zoom I inverse
| 	Deformed Zoom I midline
| 	Deformed Zoom I Line
| 	Deformed Zoom II Ascend
| 	Deformed Zoom II Ascend buttline
| 	Deformed Zoom II Ascend inverse
| 	Deformed Zoom II Ascend midline
| 	Deformed Zoom III Descend
| 	Deformed Zoom III Descend buttline
| 	Deformed Zoom III Descend inverse
| 	Deformed Zoom III Descend midline
| 	Deformed Zoom IV ADA Alternate
| 	Deformed Zoom IV ADA Alternate buttline
| 	Deformed Zoom IV ADA Alternate inverse
| 	Deformed Zoom IV ADA Alternate midline
| 	Deformed Zoom V LR
| 	Deformed Zoom V LR buttline
| 	Deformed Zoom V LR inverse
| 	Deformed Zoom V LR midline
| 	Deformed Zoom VI RL
| 	Deformed Zoom VI RL buttline
| 	Deformed Zoom VI RL inverse
| 	Deformed Zoom VI RL midline
| 	Distort Clip In Line II RL
| 	Emerge Clip III HVH Alternate
| 	Emerge Clip III HVH Alternate buttline
| 	Emerge Clip III HVH Alternate inverse
| 	Emerge Clip III HVH Alternate midline
| 	Ghost Line postline Clips
| 	Ghost Shake Syl Multi
| 	Ghost Shake Syl Multi buttline
| 	Ghost Shake Syl Multi inverse
| 	Ghost Shake Syl Multi midline
| 	Ghost Shake Syl Multi Line
| 	Ghost Shakes Simple
| 	Ghost Shakes Simple buttline
| 	Ghost Shakes Simple inverse
| 	Ghost Shakes Simple midline
| 	Ghost Shakes Simple Line
| 	Hattori Syl Cut I
| 	Hattori Syl Cut I buttline
| 	Hattori Syl Cut I inverse
| 	Hattori Syl Cut I midline
| 	Meave Light I
| 	Meave Light I buttline
| 	Meave Light I inverse
| 	Meave Light I midline
| 	Move Char I buttline
| 	Move Char I inverse
| 	Move Char I midline
| 	Move Char II Gyre buttline
| 	Move Char II Gyre inverse
| 	Move Char II Gyre midline
| 	Move Char III Ascend
| 	Move Char III Ascend buttline
| 	Move Char III Ascend inverse
| 	Move Char III Ascend midline
| 	Move Char III Ascend postword
| 	Move Char IV Ascend Multi
| 	Move Char IV Ascend Multi buttline
| 	Move Char IV Ascend Multi inverse
| 	Move Char IV Ascend Multi midline
| 	Move Char IV Ascend Multi postword
| 	Move Char V Descend
| 	Move Char V Descend buttline
| 	Move Char V Descend inverse
| 	Move Char V Descend midline
| 	Move Char V Descend postword
| 	Move Char VI Descend Multi
| 	Move Char VI Descend Multi buttline
| 	Move Char VI Descend Multi inverse
| 	Move Char VI Descend Multi midline
| 	Move Char VI Descend Multi postword
| 	Move Line Center Clip I
| 	Move Line Center Clip II
| 	Move Line Center Clip III Sequence
| 	Move Syl from Center Line I inverse
| 	Move Syl from Center Line II
| 	Move Syl from Center Line II inverse
| 	Palpitations Char
| 	Palpitations Char buttline
| 	Palpitations Char inverse
| 	Palpitations Char midline
| 	Screw Char II move
| 	Screw Char II move buttline
| 	Screw Char II move inverse
| 	Screw Char II move midline
| 	Screw Char III fry
| 	Screw Char III fry buttline
| 	Screw Char III fry inverse
| 	Screw Char III fry midline
| 	Screw Char IV fry move
| 	Screw Char IV fry move buttline
| 	Screw Char IV fry move inverse
| 	Screw Char IV fry move midline
| 	Screw Char V frz
| 	Screw Char V frz buttline
| 	Screw Char V frz inverse
| 	Screw Char V frz midline
| 	Screw Char VI frz move
| 	Screw Char VI frz move buttline
| 	Screw Char VI frz move inverse
| 	Screw Char VI frz move midline
| 	Screw Char VII Rectangle
| 	Screw Char VII Rectangle buttline
| 	Screw Char VII Rectangle inverse
| 	Screw Char VII Rectangle midline
| 	Screw Char VIII Rectangle move
| 	Screw Char VIII Rectangle move buttline
| 	Screw Char VIII Rectangle move inverse
| 	Screw Char VIII Rectangle move midline
| 	Screw Char IX Rectangle fry
| 	Screw Char IX Rectangle fry buttline
| 	Screw Char IX Rectangle fry inverse
| 	Screw Char IX Rectangle fry midline
| 	Screw Char X Rectangle fry move
| 	Screw Char X Rectangle fry move buttline
| 	Screw Char X Rectangle fry move inverse
| 	Screw Char X Rectangle fry move midline
| 	Screw Char XI Rectangle frz
| 	Screw Char XI Rectangle frz buttline
| 	Screw Char XI Rectangle frz inverse
| 	Screw Char XI Rectangle frz midline
| 	Screw Char XII Rectangle frz move
| 	Screw Char XII Rectangle frz move buttline
| 	Screw Char XII Rectangle frz move inverse
| 	Screw Char XII Rectangle frz move midline
| 	Shigatsu Op 1
| 	Snake Char I buttline
| 	Snake Char I inverse
| 	Snake Char I midline
| 	Snake Char II
| 	Snake Char II buttline
| 	Snake Char II inverse
| 	Snake Char II midline
| 	SNSD Oh
| 	SNSD Oh buttline
| 	SNSD Oh inverse
| 	SNSD Oh midline
| 	Spectrum Move Char buttline
| 	Spectrum Move Char inverse
| 	Spectrum Move Char midline
| 	Static Clip III ADA Alternate
| 	Static Clip III ADA Alternate buttline
| 	Static Clip III ADA Alternate inverse
| 	Static Clip III ADA Alternate midline
| 	Static Clip VI LRL Alternate
| 	Static Clip VI LRL Alternate buttline
| 	Static Clip VI LRL Alternate inverse
| 	Static Clip VI LRL Alternate midline
| 	Static Clip VII LTRB Alternate
| 	Static Clip VII LTRB Alternate buttline
| 	Static Clip VII LTRB Alternate inverse
| 	Static Clip VII LTRB Alternate midline
| 	Static Clip VIII Horizontal Multi I buttline
| 	Static Clip VIII Horizontal Multi I inverse
| 	Static Clip VIII Horizontal Multi I midline
| 	Static Clip IX Vertical Multi I buttline
| 	Static Clip IX Vertical Multi I inverse
| 	Static Clip IX Vertical Multi I midline
| 	Stela Move III BT
| 	Stela Move III BT buttline
| 	Stela Move III BT midline
| 	Stela Move III BT inverse
| 	Stela Move IV TB
| 	Stela Move IV TB buttline
| 	Stela Move IV TB midline
| 	Stela Move IV TB inverse
| 	Stela Move V BTB Alternate
| 	Stela Move V BTB Alternate buttline
| 	Stela Move V BTB Alternate midline
| 	Stela Move V BTB Alternate inverse
| 	Wavelet Char
| 	Wavelet Char buttline
| 	Wavelet Char inverse
| 	Wavelet Char midline
| 	
| **shape FX List**
| 	ABC Create New fx
| 	?? ????? I TL
| 	?? ????? I TL fscxy
| 	?? ????? II TL
| 	?? ????? II TL fscxy
| 	Bakura I TL
| 	Bakura II TL
| 	Before Line II Circle
| 	Bezier Heart I TL
| 	Bezier Heart II TL
| 	Bezier Snake I TL I
| 	Bezier Snake I TL II
| 	Bezier Snake II Super Star TL
| 	Bezier Snake III Super Start Double TL
| 	Big Pixel I leadin
| 	Big Pixel I leadin buttline
| 	Big Pixel I leadin inverse
| 	Big Pixel I leadin midline
| 	Big Pixel I leadout
| 	Big Pixel I leadout buttline
| 	Big Pixel I leadout inverse
| 	Big Pixel I leadout midline
| 	Big Pixel I Line
| 	Big Pixel I postline
| 	Big Pixel I preline
| 	Big Pixel I TL
| 	Blue the Stars I leadin
| 	Blue the Stars I leadin buttline
| 	Blue the Stars I leadin inverse
| 	Blue the Stars I leadin midline
| 	Blue the Stars I leadout
| 	Blue the Stars I leadout buttline
| 	Blue the Stars I leadout inverse
| 	Blue the Stars I leadout midline
| 	Blue the Stars I Line
| 	Blue the Stars I postline
| 	Blue the Stars I preline
| 	Blue the Stars I TL
| 	Blue the Stars II leadin
| 	Blue the Stars II leadin buttline
| 	Blue the Stars II leadin inverse
| 	Blue the Stars II leadin midline
| 	Blue the Stars II leadout
| 	Blue the Stars II leadout buttline
| 	Blue the Stars II leadout inverse
| 	Blue the Stars II leadout midline
| 	Blue the Stars II Line
| 	Blue the Stars II postline
| 	Blue the Stars II preline
| 	Blue the Stars II TL
| 	Circle Color Apology I HL
| 	Circle Color Apology I leadin
| 	Circle Color Apology I leadin buttline
| 	Circle Color Apology I leadin inverse
| 	Circle Color Apology I leadin midline
| 	Circle Color Apology I leadout
| 	Circle Color Apology I leadout buttline
| 	Circle Color Apology I leadout inverse
| 	Circle Color Apology I leadout midline
| 	Circle Color Apology I Line
| 	Circle Color Apology I postline
| 	Circle Color Apology I preline
| 	Circle Multi Shape I leadin
| 	Circle Multi Shape I leadin buttline
| 	Circle Multi Shape I leadin inverse
| 	Circle Multi Shape I leadin midline
| 	Circle Multi Shape I leadout
| 	Circle Multi Shape I leadout buttline
| 	Circle Multi Shape I leadout inverse
| 	Circle Multi Shape I leadout midline
| 	Circle Multi Shape I Line
| 	Circle Multi Shape I postline
| 	Circle Multi Shape I preline
| 	Cristal Fake HL
| 	Cristal Fake leadin
| 	Cristal Fake leadin buttline
| 	Cristal Fake leadin inverse
| 	Cristal Fake leadin midline
| 	Cristal Fake leadout
| 	Cristal Fake leadout buttline
| 	Cristal Fake leadout inverse
| 	Cristal Fake leadout midline
| 	Cristal Fake Line
| 	Cristal Fake preline
| 	Dollars Bills leadin
| 	Dollars Bills leadin buttline
| 	Dollars Bills leadin inverse
| 	Dollars Bills leadin midline
| 	Dollars Bills leadout
| 	Dollars Bills leadout buttline
| 	Dollars Bills leadout inverse
| 	Dollars Bills leadout midline
| 	Dollars Bills Line
| 	Dollars Bills postline
| 	Dollars Bills preline
| 	Feather Multi HL
| 	Feather Multi leadin
| 	Feather Multi leadin buttline
| 	Feather Multi leadin inverse
| 	Feather Multi leadin midline
| 	Feather Multi leadout
| 	Feather Multi leadout buttline
| 	Feather Multi leadout inverse
| 	Feather Multi leadout midline
| 	Feather Multi Line
| 	Feather Multi postline
| 	Feather Multi preline
| 	Feathers I leadin buttline
| 	Feathers I leadin inverse
| 	Feathers I leadin midline
| 	Feathers I leadout buttline
| 	Feathers I leadout inverse
| 	Feathers I leadout midline
| 	Feathers I Line
| 	Feathers I postline
| 	Feathers I preline
| 	Geometric Figures I HL
| 	Geometric Figures I leadin
| 	Geometric Figures I leadin buttline
| 	Geometric Figures I leadin inverse
| 	Geometric Figures I leadin midline
| 	Geometric Figures I leadout
| 	Geometric Figures I leadout buttline
| 	Geometric Figures I leadout inverse
| 	Geometric Figures I leadout midline
| 	Geometric Figures I Line
| 	Geometric Figures I postline
| 	Geometric Figures I preline
| 	Jump Clasic Shape IV alternate HL
| 	Motor Gear Line
| 	Natsuo Smoke I leadin buttline
| 	Natsuo Smoke I leadin inverse
| 	Natsuo Smoke I leadin midline
| 	Natsuo Smoke I leadout buttline
| 	Natsuo Smoke I leadout inverse
| 	Natsuo Smoke I leadout midline
| 	Natsuo Smoke I Line
| 	Natsuo Smoke I postline
| 	Natsuo Smoke I preline
| 	Rapsodia I leadin
| 	Rapsodia I leadin buttline
| 	Rapsodia I leadin inverse
| 	Rapsodia I leadin midline
| 	Rapsodia I leadout
| 	Rapsodia I leadout buttline
| 	Rapsodia I leadout inverse
| 	Rapsodia I leadout midline
| 	Rapsodia I Line
| 	Rapsodia I postline
| 	Rapsodia I preline
| 	Sakura Bezier Snake I HL
| 	Sakura Bezier Snake II Double HL
| 	Sakura Circle I HL
| 	Sakura Circle I leadin
| 	Sakura Circle I leadin buttline
| 	Sakura Circle I leadin inverse
| 	Sakura Circle I leadin midline
| 	Sakura Circle I leadout
| 	Sakura Circle I leadout buttline
| 	Sakura Circle I leadout inverse
| 	Sakura Circle I leadout midline
| 	Sakura Circle I Line
| 	Sakura Circle I postline
| 	Sakura Circle I preline
| 	Sakura Circle II HL
| 	Sakura Circle II leadin
| 	Sakura Circle II leadin buttline
| 	Sakura Circle II leadin inverse
| 	Sakura Circle II leadin midline
| 	Sakura Circle II leadout
| 	Sakura Circle II leadout buttline
| 	Sakura Circle II leadout inverse
| 	Sakura Circle II leadout midline
| 	Sakura Circle II Line
| 	Sakura Circle II postline
| 	Sakura Circle II preline
| 	Sakura Silkworm I preHL
| 	Sakura Silkworm II preHL
| 	Sakura Silkworm III preHL
| 	Smoke I Line II
| 	Sparkling I HL
| 	Sparkling I leadin
| 	Sparkling I leadin buttline
| 	Sparkling I leadin inverse
| 	Sparkling I leadin midline
| 	Sparkling I leadout
| 	Sparkling I leadout buttline
| 	Sparkling I leadout inverse
| 	Sparkling I leadout midline
| 	Sparkling I leadin
| 	Sparkling I Line
| 	Sparkling I postline
| 	Sparkling I preline
| 	Sparkling I TL
| 	Square Random I HL
| 	Square Random I leadin
| 	Square Random I leadin buttline
| 	Square Random I leadin inverse
| 	Square Random I leadin midline
| 	Square Random I leadout
| 	Square Random I leadout buttline
| 	Square Random I leadout inverse
| 	Square Random I leadout midline
| 	Square Random I Line
| 	Star Soul I leadin
| 	Star Soul I leadin buttline
| 	Star Soul I leadin inverse
| 	Star Soul I leadin midline
| 	Star Soul I leadout
| 	Star Soul I leadout buttline
| 	Star Soul I leadout inverse
| 	Star Soul I leadout midline
| 	Star Soul I Line
| 	Star Soul I postline
| 	Star Soul I preline
| 	Star Soul II leadin
| 	Star Soul II leadin buttline
| 	Star Soul II leadin inverse
| 	Star Soul II leadin midline
| 	Star Soul II leadout
| 	Star Soul II leadout buttline
| 	Star Soul II leadout inverse
| 	Star Soul II leadout midline
| 	Star Soul II Line
| 	Star Soul II postline
| 	Star Soul II preline
| 	Star Soul III leadin
| 	Star Soul III leadin buttline
| 	Star Soul III leadin inverse
| 	Star Soul III leadin midline
| 	Star Soul III leadout
| 	Star Soul III leadout buttline
| 	Star Soul III leadout inverse
| 	Star Soul III leadout midline
| 	Star Soul III Line
| 	Star Soul III postline
| 	Star Soul III preline
| 	Steam I leadin
| 	Steam I leadin buttline
| 	Steam I leadin inverse
| 	Steam I leadin midline
| 	Steam I leadout
| 	Steam I leadout buttline
| 	Steam I leadout inverse
| 	Steam I leadout midline
| 	Steam I Line
| 	Steam I postline
| 	Steam I preline
| 	Stick I BT HL
| 	The Damned Sakuras HL
| 	The Damned Sakuras leadin
| 	The Damned Sakuras leadin buttline
| 	The Damned Sakuras leadin inverse
| 	The Damned Sakuras leadin midline
| 	The Damned Sakuras leadout
| 	The Damned Sakuras leadout buttline
| 	The Damned Sakuras leadout inverse
| 	The Damned Sakuras leadout midline
| 	The Damned Sakuras Line
| 	The Damned Sakuras postline
| 	The Damned Sakuras preline
| 	
| **translation FX List**
| 	ABC Create New fx
| 	Agitation Char I buttline
| 	Agitation Char I inverse
| 	Agitation Char I midline
| 	Agitation Char II
| 	Animated Clip II fry buttline
| 	Animated Clip II fry inverse
| 	Animated Clip II fry midline
| 	Animated Clip V Alternate buttline
| 	Animated Clip V Alternate inverse
| 	Animated Clip V Alternate midline
| 	Animated Clips VI LLRR Alternate Line
| 	Animated Clips VI LLRR Mark Alternate Line
| 	Animated Clips XI TTBB Alternate Line
| 	Animated Clips XI TTBB Mark Alternate Line
| 	Asault Sequence buttline
| 	Asault Sequence inverse
| 	Asault Sequence midline
| 	Auxiliar Spark Shine I buttline
| 	Auxiliar Spark Shine I inverse
| 	Auxiliar Spark Shine I midline
| 	Auxiliar Spark Shine II buttline
| 	Auxiliar Spark Shine II inverse
| 	Auxiliar Spark Shine II midline
| 	Auxiliar Spark Shine III buttline
| 	Auxiliar Spark Shine III inverse
| 	Auxiliar Spark Shine III midline
| 	Char Clip 4 I
| 	Char Clip 4 I buttline
| 	Char Clip 4 I inverse
| 	Char Clip 4 I midline
| 	Char Clip 4 II
| 	Char Clip 4 II buttline
| 	Char Clip 4 II inverse
| 	Char Clip 4 II midline
| 	Char Dancing I buttline
| 	Char Dancing I inverse
| 	Char Dancing I midline
| 	Char Dancing II buttline
| 	Char Dancing II inverse
| 	Char Dancing II midline
| 	Char Delay VIII frxyz
| 	Char Random XIV RCL
| 	Char Random XV RCL number
| 	Char Random XVI LCR binary
| 	Char Random XVII midline
| 	Char Random XVIII midline numbers
| 	Char Random XIX midline binary
| 	Char Twister I buttline
| 	Char Twister I inverse
| 	Char Twister I midline
| 	Char Twister II Double buttline
| 	Char Twister II Double inverse
| 	Char Twister II Double midline
| 	Char Under Sea buttline
| 	Char Under Sea inverse
| 	Char Under Sea midline
| 	Crazy Dancing Char II
| 	Crazy Dancing Char II buttline
| 	Crazy Dancing Char II inverse
| 	Crazy Dancing Char II midline
| 	Curve Line II
| 	Curve Line II buttline
| 	Curve Line II inverse
| 	Curve Line II midline
| 	Distort Clip in Line I LR
| 	Distort Clip in Line I RL
| 	Distort Clip in Line I RR
| 	Emerge Clip Grip III buttline
| 	Emerge Clip Grip III inverse
| 	Emerge Clip Grip III midline
| 	Emerge Clip VH buttline
| 	Emerge Clip VH inverse
| 	Emerge Clip VH midline
| 	Ghost Shake Char Simple buttline
| 	Ghost Shake Char Simple inverse
| 	Ghost Shake Char Simple midline
| 	Helical Char I
| 	Helical Char I buttline
| 	Helical Char I inverse
| 	Helical Char I midline
| 	Keane Again and Again buttline
| 	Keane Again and Again inverse
| 	Keane Again and Again midline
| 	Keane Loves Is The End buttline
| 	Keane Loves Is The End inverse
| 	Keane Loves Is The End midline
| 	Keane Perfect Symmetry buttline
| 	Keane Perfect Symmetry inverse
| 	Keane Perfect Symmetry midline
| 	Move Char from Center Line buttline
| 	Move Char from Center Line inverse
| 	Move Char from Center Line midline
| 	Move Char I Random I buttline
| 	Move Char I Random I inverse
| 	Move Char I Random I midline
| 	Move Char I Random II frxyz buttline
| 	Move Char I Random II frxyz inverse
| 	Move Char I Random II frxyz midline
| 	Move Char II BB
| 	Move Char II BB buttline
| 	Move Char II BB inverse
| 	Move Char II BB midline
| 	Move Char III BB frx
| 	Move Char III BB frx buttline
| 	Move Char III BB frx inverse
| 	Move Char III BB frx midline
| 	Move Char IV BB fry
| 	Move Char IV BB fry buttline
| 	Move Char IV BB fry inverse
| 	Move Char IV BB fry midline
| 	Move Char V BB frz
| 	Move Char V BB frz buttline
| 	Move Char V BB frz inverse
| 	Move Char V BB frz midline
| 	Move Char VI BB frxyz
| 	Move Char VI BB frxyz buttline
| 	Move Char VI BB frxyz inverse
| 	Move Char VI BB frxyz midline
| 	Move Char VII BT
| 	Move Char VII BT buttline
| 	Move Char VII BT inverse
| 	Move Char VII BT midline
| 	Move Char VIII BT frx
| 	Move Char VIII BT frx buttline
| 	Move Char VIII BT frx inverse
| 	Move Char VIII BT frx midline
| 	Move Char IX BT fry
| 	Move Char IX BT fry buttline
| 	Move Char IX BT fry inverse
| 	Move Char IX BT fry midline
| 	Move Char X BT frz
| 	Move Char X BT frz buttline
| 	Move Char X BT frz inverse
| 	Move Char X BT frz midline
| 	Move Char XI BT frxyz
| 	Move Char XI BT frxyz buttline
| 	Move Char XI BT frxyz inverse
| 	Move Char XI BT frxyz midline
| 	Move Char XII TB
| 	Move Char XII TB buttline
| 	Move Char XII TB inverse
| 	Move Char XII TB midline
| 	Move Char XIII TB frx
| 	Move Char XIII TB frx buttline
| 	Move Char XIII TB frx inverse
| 	Move Char XIII TB frx midline
| 	Move Char XIV TB fry
| 	Move Char XIV TB fry buttline
| 	Move Char XIV TB fry inverse
| 	Move Char XIV TB fry midline
| 	Move Char XV TB frz
| 	Move Char XV TB frz buttline
| 	Move Char XV TB frz inverse
| 	Move Char XV TB frz midline
| 	Move Char XVI TB frxyz
| 	Move Char XVI TB frxyz buttline
| 	Move Char XVI TB frxyz inverse
| 	Move Char XVI TB frxyz midline
| 	Move Char XVII TT
| 	Move Char XVII TT buttline
| 	Move Char XVII TT inverse
| 	Move Char XVII TT midline
| 	Move Char XVIII TT frx
| 	Move Char XVIII TT frx buttline
| 	Move Char XVIII TT frx inverse
| 	Move Char XVIII TT frx midline
| 	Move Char XIX TT fry
| 	Move Char XIX TT fry buttline
| 	Move Char XIX TT fry inverse
| 	Move Char XIX TT fry midline
| 	Move Char XX TT frz
| 	Move Char XX TT frz buttline
| 	Move Char XX TT frz inverse
| 	Move Char XX TT frz midline
| 	Move Char XXI TT frxyz
| 	Move Char XXI TT frxyz buttline
| 	Move Char XXI TT frxyz inverse
| 	Move Char XXI TT frxyz midline
| 	Move Char XXII TBT Alternate
| 	Move Char XXII TBT Alternate buttline
| 	Move Char XXII TBT Alternate inverse
| 	Move Char XXII TBT Alternate midline
| 	Move Char XXIII TBT Alternate frx
| 	Move Char XXIII TBT Alternate frx buttline
| 	Move Char XXIII TBT Alternate frx inverse
| 	Move Char XXIII TBT Alternate frx midline
| 	Move Char XXIV TBT Alternate fry
| 	Move Char XXIV TBT Alternate fry buttline
| 	Move Char XXIV TBT Alternate fry inverse
| 	Move Char XXIV TBT Alternate fry midline
| 	Move Char XXV TBT Alternate frz
| 	Move Char XXV TBT Alternate frz buttline
| 	Move Char XXV TBT Alternate frz inverse
| 	Move Char XXV TBT Alternate frz midline
| 	Move Char XXVI TBT Alternate frxyz
| 	Move Char XXVI TBT Alternate frxyz buttline
| 	Move Char XXVI TBT Alternate frxyz inverse
| 	Move Char XXVI TBT Alternate frxyz midline
| 	Move Char XXVII TBT Random
| 	Move Char XXVII TBT Random buttline
| 	Move Char XXVII TBT Random inverse
| 	Move Char XXVII TBT Random midline
| 	Move Char XXVIII TBT Random frx
| 	Move Char XXVIII TBT Random frx buttline
| 	Move Char XXVIII TBT Random frx inverse
| 	Move Char XXVIII TBT Random frx midline
| 	Move Char XXIX TBT Random fry
| 	Move Char XXIX TBT Random fry buttline
| 	Move Char XXIX TBT Random fry inverse
| 	Move Char XXIX TBT Random fry midline
| 	Move Char XXX TBT Random frz
| 	Move Char XXX TBT Random frz buttline
| 	Move Char XXX TBT Random frz inverse
| 	Move Char XXX TBT Random frz midline
| 	Move Char XXXI TBT Random frxyz
| 	Move Char XXXI TBT Random frxyz buttline
| 	Move Char XXXI TBT Random frxyz inverse
| 	Move Char XXXI TBT Random frxyz midline
| 	Move Line II BT
| 	Move Line IV TB
| 	Move Line VII LR
| 	Move Line IX RL
| 	Move ShineLine I LL
| 	Move ShineLine IV RLR Alternate
| 	Palpitations char buttline
| 	Palpitations char inverse
| 	Palpitations char midline
| 	Screw Char buttline
| 	Screw Char inverse
| 	Screw Char midline
| 	Screw Char fry buttline
| 	Screw Char fry inverse
| 	Screw Char fry midline
| 	Screw Char frz buttline
| 	Screw Char frz inverse
| 	Screw Char frz midline
| 	Screw Char II Rectangle buttline
| 	Screw Char II Rectangle inverse
| 	Screw Char II Rectangle midline
| 	Screw Char II Rectangle fry buttline
| 	Screw Char II Rectangle fry inverse
| 	Screw Char II Rectangle fry midline
| 	Screw Char II Rectangle frz buttline
| 	Screw Char II Rectangle frz inverse
| 	Screw Char II Rectangle frz midline
| 	Screw III MultiColor Border buttline
| 	Screw III MultiColor Border inverse
| 	Screw III MultiColor Border midline
| 	Snake Char I LR
| 	Snake Char I LR buttline
| 	Snake Char I LR inverse
| 	Snake Char I LR midline
| 	Snake Char II RL buttline
| 	Snake Char II RL inverse
| 	Snake Char II RL midline
| 	Snake Char III LR frx
| 	Snake Char III LR frx buttline
| 	Snake Char III LR frx inverse
| 	Snake Char III LR frx midline
| 	Snake Char IV RL frx buttline
| 	Snake Char IV RL frx inverse
| 	Snake Char IV RL frx midline
| 	SNSD Oh buttline
| 	SNSD Oh inverse
| 	SNSD Oh midline
| 	Spectrum Move Char buttline
| 	Spectrum Move Char inverse
| 	Spectrum Move Char midline
| 	Static Clip I Ascend Ascend buttline
| 	Static Clip I Ascend Ascend inverse
| 	Static Clip I Ascend Ascend midline
| 	Static Clip II Ascend Descend
| 	Static Clip II Ascend Descend buttline
| 	Static Clip II Ascend Descend inverse
| 	Static Clip II Ascend Descend midline
| 	Static Clip III Descend Ascend
| 	Static Clip III Descend Ascend buttline
| 	Static Clip III Descend Ascend inverse
| 	Static Clip III Descend Ascend midline
| 	Static Clip IV Descend Descend buttline
| 	Static Clip IV Descend Descend inverse
| 	Static Clip IV Descend Descend midline
| 	Static Clip V ADA Alternate
| 	Static Clip V ADA Alternate buttline
| 	Static Clip V ADA Alternate inverse
| 	Static Clip V ADA Alternate midline
| 	Static Clip VI LL buttline
| 	Static Clip VI LL inverse
| 	Static Clip VI LL midline
| 	Static Clip VII LR buttline
| 	Static Clip VII LR inverse
| 	Static Clip VII LR midline
| 	Static Clip VIII RL
| 	Static Clip VIII RL buttline
| 	Static Clip VIII RL inverse
| 	Static Clip VIII RL midline
| 	Static Clip IX RR buttline
| 	Static Clip IX RR inverse
| 	Static Clip IX RR midline
| 	Static Clip X LRL Alternate
| 	Static Clip X LRL Alternate buttline
| 	Static Clip X LRL Alternate inverse
| 	Static Clip X LRL Alternate midline
| 	Static Clip XI Horizontal Multi I buttline
| 	Static Clip XI Horizontal Multi I inverse
| 	Static Clip XI Horizontal Multi I midline
| 	Static Clip XI Horizontal Multi II buttline
| 	Static Clip XI Horizontal Multi II inverse
| 	Static Clip XI Horizontal Multi II midline
| 	Static Clip XII Vertical Multi I buttline
| 	Static Clip XII Vertical Multi I inverse
| 	Static Clip XII Vertical Multi I midline
| 	Static Clip XII Vertical Multi II buttline
| 	Static Clip XII Vertical Multi II inverse
| 	Static Clip XII Vertical Multi II midline
| 	Static Clip XII Vertical Multi III
| 	Static Clip XII Vertical Multi III buttline
| 	Static Clip XII Vertical Multi III inverse
| 	Static Clip XII Vertical Multi III midline
| 	Stela Move Char I LL buttline
| 	Stela Move Char I LL inverse
| 	Stela Move Char I LL midline
| 	Stela Move Char II LR
| 	Stela Move Char II LR buttline
| 	Stela Move Char II LR inverse
| 	Stela Move Char II LR midline
| 	Stela Move Char III RL
| 	Stela Move Char III RL buttline
| 	Stela Move Char III RL inverse
| 	Stela Move Char III RL midline
| 	Stela Move Char IV RR
| 	Stela Move Char IV RR buttline
| 	Stela Move Char IV RR inverse
| 	Stela Move Char IV RR midline
| 	Stela Move Char V RLR Alternate
| 	Stela Move Char V RLR Alternate buttline
| 	Stela Move Char V RLR Alternate inverse
| 	Stela Move Char V RLR Alternate midline
| 	Stela Move Char VI BB
| 	Stela Move Char VI BB buttline
| 	Stela Move Char VI BB inverse
| 	Stela Move Char VI BB midline
| 	Stela Move Char VII BT
| 	Stela Move Char VII BT buttline
| 	Stela Move Char VII BT inverse
| 	Stela Move Char VII BT midline
| 	Stela Move Char VIII TB
| 	Stela Move Char VIII TB buttline
| 	Stela Move Char VIII TB inverse
| 	Stela Move Char VIII TB midline
| 	Stela Move Char IX TT
| 	Stela Move Char IX TT buttline
| 	Stela Move Char IX TT inverse
| 	Stela Move Char IX TT midline
| 	Stela Move Char X TBT Alternate
| 	Stela Move Char X TBT Alternate buttline
| 	Stela Move Char X TBT Alternate inverse
| 	Stela Move Char X TBT Alternate midline
| 	Tremor Clip II Word
| 	Tremor Clip II Word leadinout
| 	Tremor Clip II Word buttline
| 	Tremor Clip II Word inverse
| 	Tremor Clip II Word midline
| 	Tremor Clip IV Word
| 	Tremor Clip IV Word leadinout
| 	Tremor Clip IV Word buttline
| 	Tremor Clip IV Word inverse
| 	Tremor Clip IV Word midline