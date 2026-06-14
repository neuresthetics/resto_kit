# resto_kit

**A systematic, job-agnostic personal knowledge base and decision-support system for water damage restoration work, built to be loaded into an AI voice assistant for faster, more consistent field decisions.**

## Purpose

This repo exists to make daily work easier and more consistent. It holds my personal standards, decision logic, equipment rules, and procedures so I can offload mental inventory and focus on the actual job in front of me.

![resto_kit](https://github.com/neuresthetics/resto_kit/blob/main/img/resto_kit_0.jpeg)

## Development


```txt
resto_kit/
├── framework                          <str>
├── meta
│   ├── description                    <str>
│   └── repository                     <str>
├── index
│   └── AI                             <str>   ← (the instruction you gave)
├── safety                             <str>
├── primary_scope                      <str>
├── language_system
│   ├── description                    <str>
│   ├── levels
│   │   ├── required                   {level, meaning, when_to_use}
│   │   ├── recommended                {level, meaning, when_to_use}
│   │   └── optional                   {level, meaning, when_to_use}
│   └── usage_notes
│       ├── priority                   <str>
│       ├── clarity                    <str>
│       └── voice_usage                <str>
├── modes
│   ├── rookie
│   │   ├── name, description, tone, depth, when_to_use
│   │   └── behavior_rules             [list of str]
│   ├── tech
│   │   ├── name, description, tone, depth, when_to_use
│   │   └── behavior_rules             [list of str]
│   ├── science_nerd
│   │   ├── name, description, tone, depth, when_to_use
│   │   └── behavior_rules             [list of str]
│   └── developer
│       ├── name, description, tone, depth, when_to_use
│       └── behavior_rules             [list of str]
├── base_science
│   ├── psychrometry
│   │   ├── description
│   │   ├── core_concepts              {temperature, relative_humidity, grains_per_pound, dew_point, vapor_pressure}
│   │   ├── key_relationships          {vapor_pressure_gradient, temperature_effect, rh_vs_gpp}
│   │   ├── field_implications         {drying_strategy, monitoring_value, small_spaces}
│   │   └── common_misunderstandings   {rh_is_enough, hot_air_dries_faster}
│   ├── moisture_physics
│   │   ├── description
│   │   ├── core_concepts              {porosity, permeability, wicking, free_water, bound_moisture, absorption_vs_adsorption}
│   │   ├── key_relationships          {material_type_matters, time_and_penetration, vapor_barriers}
│   │   ├── field_implications         {drying_difficulty, removal_decisions, hidden_moisture_risk, vapor_barrier_problems}
│   │   └── common_misunderstandings   {all_materials_dry_the_same, surface_dry_means_dry, extraction_fixes_everything}
│   ├── evaporation_principles
│   │   ├── description
│   │   ├── core_concepts              {evaporation, boundary_layer, vapor_pressure_gradient, air_movement}
│   │   ├── key_relationships          {airflow_and_evaporation, temperature_and_evaporation, humidity_and_evaporation, air_movers_vs_dehumidifiers}
│   │   ├── field_implications         {air_mover_placement, boundary_layer_disruption, small_room_overheating, equipment_balance}
│   │   └── common_misunderstandings   {more_air_is_always_better, fans_dry_by_themselves, pointing_fans_at_walls}
│   ├── material_behavior
│   │   ├── description
│   │   ├── drywall, dimensional_lumber, hardwood_flooring, particle_board_and_mdf, concrete_and_slabs
│   │   ├── insulation                 {fiberglass, cellulose, closed_cell_spray_foam}
│   │   ├── carpet_and_pad, lvp_and_sheet_vinyl
│   │   ├── tile_and_grout             {grout_readings, fiber_cement_false_readings, thermal_camera_limitations, drying_approach, field_note}
│   │   ├── electronics_and_appliances, fabrics_and_upholstery, documents_and_photos
│   │   ├── key_relationships          {material_type_drives_decisions, time_changes_behavior}
│   │   └── field_implications         {removal_vs_drying, vapor_barriers, electronics_caution}
│   ├── dry_standards_by_material
│   │   ├── core_principle
│   │   ├── wood                         {measurement, target, priority}
│   │   ├── non_wood_materials
│   │   ├── insulation_rule              {rule, exceptions, priority}
│   │   ├── drywall_rule                 {category1_short_dwell, category2_or_3_or_long_dwell, priority}
│   │   └── class4_specialty_drying      {description, approach, voice_note}
│   ├── contamination_science
│   │   ├── description
│   │   ├── core_concepts                {contamination_level}
│   │   ├── key_relationships            {time_and_risk}
│   │   ├── field_implications           {removal_decisions, containment_urgency, ppe_escalation}
│   │   └── common_misunderstandings     {clean_water_stays_clean, surface_clean_is_enough}
│   ├── airflow_and_ventilation
│   │   ├── description
│   │   ├── core_concepts                {boundary_layer_disruption, directed_airflow, general_circulation, negative_pressure_interaction}
│   │   ├── key_relationships            {airflow_and_dehumidification, airflow_and_contamination, velocity_vs_volume, small_space_dynamics}
│   │   ├── field_implications           {air_mover_placement, equipment_balance, containment_considerations, monitoring_airflow}
│   │   └── common_misunderstandings     {more_fans_is_always_better, pointing_fans_directly_at_walls, fans_remove_moisture}
│   ├── thermodynamics_basics
│   │   ├── description
│   │   ├── core_concepts                {heat_energy, latent_heat_of_vaporization, air_moisture_capacity, energy_balance}
│   │   ├── key_relationships            {temperature_and_drying_rate, heat_without_removal, small_space_heating, evaporative_cooling}
│   │   ├── field_implications           {heat_as_a_tool, equipment_interaction, small_room_management, monitoring_temperature}
│   │   └── common_misunderstandings     {hotter_is_always_faster, dehumidifiers_work_better_when_hot, ignoring_temperature}
│   ├── corrosion_and_degradation
│   │   ├── description
│   │   ├── core_concepts                {corrosion, acidic_smoke_residue, hidden_corrosion, electrolytic_corrosion, post_fire_water_synergy, chemical_corrosion}
│   │   ├── key_relationships            {smoke_plus_moisture, time_and_corrosion, electronics_vulnerability, hvac_as_distribution_system, chemical_cause_of_loss}
│   │   ├── field_implications           {electronics_recommendations, hvac_assessment, hidden_areas_priority, communication_with_customers, drying_priority, chemical_loss_assessment}
│   │   └── common_misunderstandings     {if_it_works_it_is_fine, cleaning_removes_the_risk, only_fire_jobs_have_corrosion, surface_dry_means_safe, drano_is_just_water}
│   ├── materials
│   │   ├── insulation                   {rule, why, exceptions, measurement, voiceNote, priority, dry_standard_ref}
│   │   ├── drywall                      {category1, category2or3OrLongDwell, measurement, redFlagsForRemovalEvenOnCat1, voiceNote, priority}
│   │   ├── unfinishedWoodFramingSubfloor, hardwoodFlooring, engineeredWoodLaminateLVP, concreteSlab, carpetAndPad, plasterLath, cabinetry, tileStoneOverSubstrate, contentsElectronicsDocumentsFabrics
│   │   ├── quickReferenceTable          [list of dicts]
│   │   ├── workingRulesSummary          [list of str]
│   │   └── voiceUsageExamples           [list of str]
│   └── (other base_science sections as listed above)
├── mold
│   ├── description
│   ├── core_concepts                    {conditions_for_growth, microbial_amplification, dwell_time_effect, category_migration, hidden_mold_risk}
│   ├── key_relationships                {time_and_risk, temperature_and_growth, material_as_food_source, aerosolization_risk, category_effect_on_risk}
│   ├── field_implications               {red_flags_for_hidden_or_active_mold [list], when_to_treat_as_higher_risk [list], removal_vs_drying, containment_and_controls, drying_approach_on_mold_jobs, field_tips_and_working_rules [list]}
│   └── common_misunderstandings         {clean_water_stays_clean, surface_clean_is_enough, no_smell_means_no_contamination}
├── equipment
│   ├── meta
│   ├── general_principles               [list of str]
│   ├── dehumidifiers                    {types, sizing_rules_of_thumb, placement [list], monitoring_performance [list], common_mistakes [list]}
│   ├── air_movers                       {types, placement_principles [list], quantity_rules [list], common_mistakes [list]}
│   ├── portable_extractors              {why_it_matters, technique [list], when_especially_important [list], limitations}
│   ├── air_filtration_devices           {types, when_to_use [list], setup_tips [list], common_mistakes [list]}
│   ├── ulv_foggers                      {purpose, when_to_use [list], when_not_to_use [list], safety_requirements [list], operation_notes [list]}
│   ├── sizing_and_capacity              {quick_assessment_order [list], small_spaces_rule, combined_air_volumes}
│   ├── placement_and_usage              {core_idea, key_tips [list]}
│   ├── taping_and_routing               {description, required [list], voice_prompt}
│   └── performance_monitoring           {daily_checks [list], temperature_and_humidity}
├── job_functions
│   ├── description
│   ├── service_contract                 {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
│   ├── initial_assessment               {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
│   ├── source_control                   {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
│   ├── extraction                       {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
│   ├── contents_handling                {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
│   ├── engineering_controls             {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
│   ├── containment
│   │   ├── coreMindset
│   │   ├── whenToUse                    {always, airVolume, demo, isolation}
│   │   ├── recommendedSequence          [list of str]
│   │   ├── zipperDoors                  {singleZipper, doubleZipper, placementNote}
│   │   └── types                        [list]
│   ├── selective_demolition
│   │   ├── description, key_activities, critical_decision_points, practical_guidance, category_specific_guidance, safety_and_hazmat, common_mistakes, voice_considerations
│   │   └── remove_vs_dry_criteria       {generally_remove [list], consider_minimal_removal_first [list]}
│   ├── demo_order
│   │   ├── name, description, steps     [list of str]
│   │   └── demo_final_cleaning          {description, key_activities [list], alt {title, category, conditions}, critical_decision_points, practical_guidance, voice_considerations, real_world_notes}
│   ├── plumbing_electrical
│   │   ├── meta
│   │   ├── plumbing                     {water_shutoffs, common_issues, when_to_involve_a_licensed_plumber, old_plumbing_considerations, field_tips}
│   │   ├── electrical                   {gfci_protection, common_hazards, when_to_involve_a_licensed_electrician, old_electrical_systems, field_tips, lockout_tagout}
│   │   └── combined_considerations      [list]
│   ├── crawlspaces
│   │   ├── safety                       {atmospheric_testing, ppe {respirator, other}}
│   │   ├── access_and_etiquette         {rules [list], manpower}
│   │   ├── inspection                   {key_things_to_look_for [list], voiceNote}
│   │   ├── wet_insulation               {priority, core_rule, best_practice, field_reality, voiceNote}
│   │   ├── air_movement_and_pressure    {core_rule, key_guidance [list], voiceNote}
│   │   ├── drying_techniques            {localized_tenting {description, method [list], voiceNote}, negative_air_setup}
│   │   ├── cleaning                     {ulv_fogging}
│   │   ├── vapor_barrier                {guidance, code_requirements}
│   │   └── ultra_ppe                    {when_to_use, setup, voiceNote}
│   ├── drying_and_monitoring
│   │   ├── description, key_activities, critical_decision_points, practical_guidance, voice_considerations
│   │   └── tenting                      {meta, description, when_to_use [list], when_not_to_use [list], setup_guidelines, field_tips [list], limitations_and_risks [list], related_techniques [list]}
│   ├── general_cleaning                 {description, coreApproach, practicalTips [list], voiceNote}
│   ├── trash_management_and_logistics
│   │   ├── description
│   │   ├── coreApproaches               {cleanAsYouGo, lightweightWaste, batchThenClean}
│   │   ├── dailyHandling                {staging, hauling}
│   │   ├── vehicleLoading               {dumpTruck, cargoVan}
│   │   ├── contaminatedMaterial         {description, methods [list], location}
│   │   ├── equipmentDecisions           {van, dumpster, chute}
│   │   └── keyPrinciples                [list of str]
│   ├── final_verification               {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
│   └── closeout_and_documentation       {description, key_activities [list], critical_decision_points [list], practical_guidance [list], voice_considerations}
└── project_manager_timeline
    ├── description
    ├── notes
    ├── days
    │   ├── day1                         {name, goals, key_tasks [list]}
    │   ├── day2                         {name, goals, key_tasks [list]}
    │   ├── monitoring                   {name, goals, key_tasks [list], typical_duration}
    │   └── final                        {name, goals, key_tasks [list]}
    └── mindset                          [list of str]

 ```