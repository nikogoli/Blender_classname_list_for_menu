# メニュー追加先の候補の一覧 (2.91)
-------------------------------------
* 以下の表は、`dir(bpy.types)`の結果のうち、`PT, MT, OT, HT, UL`を含むものを示す
* [Blender 3D: Noob to Proの表](https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro/Advanced_Tutorials/Python_Scripting/Object,_Action,_Settings#Undocumented_Blender) をアップデートしたようなもの
* 「Blender 2.91 の初期プロジェクト + アドオンを全て無効化」の状態で作成
* この表は、追加したメニューが実際に表示されることは保証しない


## 名前を簡略化した分類テーブル
`xxx 系`は、`xxx_yyy`や`xxx_zzz`など細かいサブタイプが存在することを示す。<br>
サブタイプの詳細は、details タブにある。<br>
(セル幅の影響で"UL"の列が隠れているので、表示させる場合は表内で横スクロールを行う)

||PT|MT|OT|HT|UL|
|----|----|----|----|----|----|
|DATA|iksolver_itasc<br>pathanim<br>text_boxes<br>metaball 系<br>curve_texture_space<br>motion 系<br>skeleton<br>EEVEE 系<br>face_maps<br>remesh<br>active_spline<br>distance<br>context 系<br>falloff_curve<br>mball_texture_space<br>area<br>customdata<br>lattice<br>modifiers<br>spot<br>shader_fx<br>bone_groups<br>shape 系<br>uv_texture<br>hair_attributes<br>custom 系<br>pose_library<br>speaker<br>display<br>normals<br>lens<br>vertex 系<br>texture_space<br>gpencil 系<br>sculpt_vertex_colors<br>font 系<br>pointcloud_attributes<br>volume 系<br>light<br>cone<br>camera 系<br>empty 系<br>preview<br>geometry 系<br>lightprobe 系<br>paragraph 系|bone_group_context_menu||||
|VOLUME|||||grids|
|BONE|bDampTrackConstraint<br>bFollowPathConstraint<br>bTrackToConstraint<br>bChildOfConstraint<br>bLocLimitConstraint<br>bPivotConstraint<br>bObjectSolverConstraint<br>context_bone<br>bKinematicConstraint<br>constraints<br>relations<br>curved<br>bSizeLimitConstraint<br>bShrinkwrapConstraint<br>bDistLimitConstraint<br>bTransformCacheConstraint<br>bRotateLikeConstraint<br>transform<br>bArmatureConstraint 系<br>bFollowTrackConstraint<br>inverse_kinematics<br>bCameraSolverConstraint<br>bMinMaxConstraint<br>bTransformConstraint 系<br>custom_props<br>bLockTrackConstraint<br>bSizeLikeConstraint<br>display 系<br>bActionConstraint 系<br>bLocateLikeConstraint<br>deform<br>bPythonConstraint<br>bSameVolumeConstraint<br>bClampToConstraint<br>bRotLimitConstraint<br>bStretchToConstraint<br>bTransLikeConstraint<br>bSplineIKConstraint 系|||||
|PROPERTIES|navigation_bar|||header||
|RIGIDBODY|||object_settings_copy<br>bake_to_keyframes<br>connect|||
|PREFERENCES|||app_template_install<br>copy_prev<br>studiolight 系<br>keyitem 系<br>keyconfig 系<br>theme_install<br>addon 系<br>keymap_restore|||
|SCENE|scene<br>physics<br>keyframing_settings<br>audio<br>custom_props<br>keying 系<br>rigid 系<br>unit||freestyle 系<br>gpencil 系||keying_set_paths|
|VIEW3D|collections<br>slots_projectpaint<br>view3d 系<br>object_type_visibility<br>paint 系<br>active 系<br>context_properties<br>grease_pencil<br>overlay 系<br>transform_orientations<br>stencil_projectpaint<br>shading 系<br>annotation_onion<br>snapping<br>gpencil 系<br>sculpt 系<br>tools 系<br>gizmo_display<br>proportional_edit<br>quad_view<br>mask|editor_menus<br>metaball_add<br>curve_add<br>armature 系<br>object 系<br>paint 系<br>lightprobe_add<br>face 系<br>hook<br>view 系<br>pivot_pie<br>assign_material<br>angle_control<br>mirror<br>image_add<br>orientations_pie<br>transform 系<br>bone 系<br>particle 系<br>uv_map<br>surface_add<br>pose 系<br>shading 系<br>vertex 系<br>select 系<br>gpencil 系<br>mesh_add<br>sculpt 系<br>tools 系<br>volume_add<br>make 系<br>light_add<br>camera_add<br>add<br>weight_gpencil<br>proportional_editing_falloff_pie<br>brush 系<br>wpaint_vgroup_lock_pie<br>snap 系<br>edit 系<br>mask|edit 系<br>transform_gizmo_set|header<br>tool_header||
|CLOTH|presets||preset_add|||
|SAFE_AREAS|presets||preset_add|||
|NODE_EEVEE_MATERIAL|settings|||||
|GPENCIL||layer 系<br>move_to_layer<br>material 系<br>cleanup<br>snap 系<br>gpencil 系|tint_flip<br>mesh_bake||masks<br>matslots<br>layer<br>annotation_layer<br>vgroups|
|WM||toolsystem_submenu<br>splash 系<br>operator_presets|previews 系<br>tool 系<br>toolbar 系<br>sysinfo<br>batch_rename<br>drop_blend_file<br>operator 系<br>keyconfig_preset_add<br>owner 系<br>properties 系<br>url 系<br>doc 系<br>path_open<br>blend_strings_utf8_validate<br>context 系<br>interface_theme_preset_add|||
|TOPBAR|name<br>tool 系<br>annotation_layers<br>gpencil 系|file 系<br>app 系<br>editor_menus<br>help<br>workspace_menu<br>render<br>templates_more<br>edit 系<br>window||upper_bar||
|COLLECTION||context_menu||||
|SCRIPT|||execute_preset|||
|TIME|keyframing_settings<br>playback<br>auto_keyframing|marker<br>cache<br>editor_menus<br>view||||
|WORLD|context_world<br>viewport_display<br>custom_props|||||
|ANIM|||update_animated_transform_constraints<br>clear_useless_actions<br>keying_set_export|||
|WORKSPACE|addons<br>main<br>custom_props|||||
|CONSTRAINT|||remove_target<br>disable_keep_transform<br>add_target<br>normalize_target_weights|||
|NODE_WORLD|viewport_display|||||
|USERPREF|file 系<br>ndof_settings<br>save_preferences<br>saveload 系<br>addons<br>input 系<br>animation 系<br>experimental 系<br>studiolight 系<br>theme 系<br>viewport 系<br>navigation 系<br>keymap<br>edit 系<br>system 系<br>interface 系|view<br>editor_menus<br>save_load<br>keyconfigs<br>interface_theme_presets||header||
|VIEWLAYER|freestyle 系<br>layer<br>eevee 系||||linesets|
|PAINT|||vertex_color_dirt|||
|NODE|quality<br>node_color_presets<br>material_slots<br>backdrop<br>annotation<br>active 系<br>texture_mapping<br>tools_active|view<br>category 系<br>editor_menus<br>node 系<br>add<br>select<br>context_menu|node_color_preset_add<br>tree_path_parent<br>collapse_hide_unused_toggle<br>add 系|header|interface_sockets|
|FILEBROWSER|directory_path<br>bookmarks 系<br>filter<br>display<br>advanced_filter|view<br>editor_menus<br>bookmarks_context_menu<br>select<br>context_menu||header|dir|
|CAMERA|presets||preset_add|||
|STATUSBAR||||header||
|INFO||view<br>editor_menus<br>area<br>context_menu<br>info||header||
|EEVEE_WORLD|mist<br>surface<br>volume|||||
|POINTCLOUD||add_attribute|||attributes|
|SIMULATION|||new|||
|EEVEE_MATERIAL|settings<br>surface<br>viewport_settings<br>context_material<br>volume|||||
|MASK||animation<br>add<br>visibility<br>select<br>mask<br>transform|||layers|
|SEQUENCER|view 系<br>effect 系<br>frame_overlay<br>time<br>scene<br>strip 系<br>custom_props<br>modifiers<br>mask<br>preview<br>cache_settings<br>proxy_settings<br>annotation 系<br>source<br>active_tool<br>adjust 系<br>tools_active|change<br>view 系<br>editor_menus<br>strip 系<br>add 系<br>marker<br>proxy<br>select 系<br>navigation<br>preview_zoom<br>range<br>context_menu|crossfade_sounds<br>fades 系<br>split_multicam<br>deinterlace_selected_movies|header<br>tool_header||
|MESH||vertex_group_context_menu<br>shape_key_context_menu|primitive_torus_add<br>select 系<br>faces_mirror_uv||shape_keys<br>vcols<br>fmaps<br>uvmaps<br>vgroups|
|FLUID|presets||preset_add|||
|UV|||lightmap_pack<br>follow_active_quads|||
|IMAGE|view 系<br>uv 系<br>scope_sample<br>render_slots<br>proportional_edit<br>image_properties<br>annotation<br>overlay 系<br>paint 系<br>snapping<br>udim 系<br>active 系<br>mask 系<br>sample_line<br>tools 系|view 系<br>editor_menus<br>pivot_pie<br>uvs 系<br>image 系<br>select 系<br>mask_context_menu|external_edit<br>project 系|header<br>tool_header|render_slots<br>udim_tiles|
|OUTLINER|filter|editor_menus<br>collection 系<br>object<br>edit_datablocks<br>context 系||header||
|TEXT|properties<br>find|view 系<br>text<br>editor_menus<br>format<br>templates 系<br>edit 系<br>select<br>context_menu||footer<br>header||
|GRAPH|filters|view<br>editor_menus<br>pivot_pie<br>key 系<br>channel 系<br>marker<br>delete<br>snap_pie<br>select<br>context_menu||header||
|NODE_DATA|EEVEE_light<br>light|||||
|RENDER|ffmpeg_presets<br>frame_remapping<br>stereoscopy<br>simplify 系<br>presets<br>color 系<br>freestyle<br>output 系<br>post_processing<br>dimensions<br>eevee 系<br>stamp 系<br>encoding 系<br>context<br>gpencil<br>opengl 系|framerate_presets<br>lineset_context_menu|preset_add<br>play_rendered_anim||renderviews|
|MATERIAL|custom_props<br>viewport<br>freestyle_line<br>preview<br>gpencil 系|context_menu|||matslots|
|CONSOLE||view<br>editor_menus<br>language<br>context_menu<br>console|execute<br>autocomplete<br>copy_as_script<br>language<br>banner|header||
|NLA|filters|view<br>editor_menus<br>channel_context_menu<br>add<br>marker<br>snap_pie<br>edit 系<br>select<br>context_menu|bake|header||
|PARTICLE|force 系<br>boidbrain<br>physics 系<br>hair 系<br>custom_props<br>vertexgroups<br>render 系<br>cache<br>emission 系<br>children 系<br>textures<br>velocity<br>rotation 系<br>field_weights<br>context_particles<br>draw|context_menu|hair_dynamics_preset_add||particle_systems|
|CLIP|footage<br>stabilization<br>camera_presets<br>track 系<br>clip_display<br>tracking 系<br>plane_track<br>marker 系<br>proxy<br>annotation<br>display<br>active 系<br>objects<br>mask 系<br>tools 系|view 系<br>pivot_pie<br>track 系<br>tracking 系<br>clip<br>stabilize 系<br>marker_pie<br>proxy<br>reconstruction 系<br>solving_pie<br>masking_editor_menus<br>select 系|camera_preset_add<br>bundles_to_mesh<br>track 系<br>tracking_settings_preset_add<br>set 系<br>constraint_to_fcurve<br>filter_tracks<br>delete_proxy<br>setup_tracking_scene|header|tracking_objects|
|DOPESHEET|filters<br>gpencil 系|view<br>editor_menus<br>key 系<br>channel 系<br>marker<br>delete<br>snap_pie<br>select<br>context_menu<br>gpencil 系||header||
|UI|||||list|
|NODE_MATERIAL|viewport|||||
|TEXTURE|voronoi 系<br>clouds<br>node<br>colors 系<br>custom_props<br>marble<br>stucci<br>preview<br>image 系<br>mapping<br>musgrave<br>magic<br>blend<br>distortednoise<br>influence<br>context<br>wood|context_menu|||texpaintslots<br>texslots|
|HAIR||add_attribute|||attributes|
|OBJECT|bDampTrackConstraint<br>bFollowPathConstraint<br>instancing 系<br>collections<br>bTrackToConstraint<br>bChildOfConstraint<br>bLocLimitConstraint<br>delta_transform<br>bPivotConstraint<br>motion 系<br>bObjectSolverConstraint<br>context_object<br>bKinematicConstraint<br>constraints<br>relations<br>bSizeLimitConstraint<br>bShrinkwrapConstraint<br>bDistLimitConstraint<br>bTransformCacheConstraint<br>bRotateLikeConstraint<br>transform<br>bArmatureConstraint 系<br>bFollowTrackConstraint<br>bCameraSolverConstraint<br>bMinMaxConstraint<br>bTransformConstraint 系<br>custom_props<br>bLockTrackConstraint<br>bSizeLikeConstraint<br>display<br>bActionConstraint 系<br>bLocateLikeConstraint<br>bPythonConstraint<br>bSameVolumeConstraint<br>bClampToConstraint<br>bRotLimitConstraint<br>bStretchToConstraint<br>visibility<br>bTransLikeConstraint||make_dupli_face<br>load 系<br>randomize_transform<br>shape_key_transfer<br>hide_render_clear_all<br>transforms_to_deltas<br>subdivision_set<br>instance_offset_from_cursor<br>assign_property_defaults<br>quick 系<br>anim_transforms_to_deltas<br>isolate_type_render<br>join_uvs<br>align<br>select 系|||
|PHYSICS|collections<br>cloth 系<br>adaptive_domain<br>cache<br>fire<br>dynamic 系<br>settings<br>export<br>viewport 系<br>softbody 系<br>smoke 系<br>dp 系<br>flow 系<br>liquid<br>particles<br>rigid 系<br>fluid<br>field 系<br>mesh<br>noise<br>borders<br>diffusion<br>collision 系<br>guide<br>add||||dynapaint_surfaces|


### ソース
この表は、[このjsonファイル](https://gist.githubusercontent.com/nikogoli/d6a06036f24294f426a289650e417c47/raw/973c2783218425be0c1af9795a03a71ec67ea155/details.json)を元に作成している