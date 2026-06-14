# resto_kit

**A systematic, job-agnostic personal knowledge base and decision-support system for water damage restoration work, built to be loaded into an AI voice assistant for faster, more consistent field decisions.**

## Purpose

This repo exists to make daily work easier and more consistent. It holds my personal standards, decision logic, equipment rules, and procedures so I can offload mental inventory and focus on the actual job in front of me.

![resto_kit](https://github.com/neuresthetics/resto_kit/blob/main/img/resto_kit_0.jpeg)

## Development


RestoKit Framework – Navigation Map
====================================

base_science/
├── psychrometry/
│   ├── core_concepts/
│   ├── key_relationships/
│   ├── field_implications/
│   └── common_misunderstandings/
├── moisture_physics/
│   ├── core_concepts/
│   ├── key_relationships/
│   ├── field_implications/
│   └── common_misunderstandings/
├── evaporation_principles/
│   ├── core_concepts/
│   ├── key_relationships/
│   ├── field_implications/
│   └── common_misunderstandings/
├── material_behavior/
│   ├── drywall
│   ├── dimensional_lumber
│   ├── hardwood_flooring
│   ├── particle_board_and_mdf
│   ├── concrete_and_slabs
│   ├── insulation/
│   │   ├── fiberglass
│   │   ├── cellulose
│   │   └── closed_cell_spray_foam
│   ├── carpet_and_pad
│   ├── lvp_and_sheet_vinyl
│   ├── tile_and_grout/
│   │   ├── grout_readings
│   │   ├── fiber_cement_false_readings
│   │   ├── thermal_camera_limitations
│   │   ├── drying_approach
│   │   └── field_note
│   ├── thinset/                              ← NEW
│   │   ├── core_behavior/
│   │   ├── water_under_liner_scenario/
│   │   ├── important_caveats/
│   │   │   ├── no_guarantees
│   │   │   ├── check_installation
│   │   │   └── risk_vs_cost
│   │   ├── field_implications/
│   │   └── voice_note
│   ├── electronics_and_appliances
│   ├── fabrics_and_upholstery
│   └── documents_and_photos
├── dry_standards_by_material/
│   ├── wood
│   ├── non_wood_materials
│   ├── insulation_rule
│   ├── drywall_rule
│   └── class4_specialty_drying
├── contamination_science/
│   ├── core_concepts/
│   ├── key_relationships/
│   ├── field_implications/
│   └── common_misunderstandings/
├── airflow_and_ventilation/
│   ├── core_concepts/
│   ├── key_relationships/
│   ├── field_implications/
│   └── common_misunderstandings/
├── thermodynamics_basics/
│   ├── core_concepts/
│   ├── key_relationships/
│   ├── field_implications/
│   └── common_misunderstandings/
├── corrosion_and_degradation/
│   ├── core_concepts/
│   ├── key_relationships/
│   ├── field_implications/
│   └── common_misunderstandings/
├── mold/
│   ├── core_concepts/
│   ├── key_relationships/
│   └── field_implications/
│       ├── red_flags_for_hidden_or_active_mold/
│       ├── when_to_treat_as_higher_risk/
│       ├── removal_vs_drying
│       ├── containment_and_controls/
│       ├── drying_approach_on_mold_jobs
│       └── field_tips_and_working_rules/
└── materials/
    ├── insulation
    ├── drywall
    ├── unfinished_wood_framing_subfloor
    ├── hardwood_flooring
    ├── engineered_wood_laminateLVP
    ├── concrete_slab
    ├── carpet_and_pad
    ├── plaster_lath
    ├── cabinetry
    ├── tile_stone_over_substrate/
    │   ├── key_issue
    │   ├── target
    │   ├── measurement
    │   ├── common_decision
    │   └── thinset_liner_interaction/        ← NEW
    └── contents_electronics_documents_fabrics

job_functions/
├── service_contract
├── initial_assessment
├── source_control
├── extraction
├── contents_handling
├── engineering_controls
├── containment
├── selective_demolition/
│   ├── remove_vs_dry_criteria/
│   │   ├── generally_remove
│   │   └── consider_minimal_removal_first
│   ├── chasing_the_water/                    ← NEW
│   │   ├── common_hidden_paths/
│   │   ├── field_reality
│   │   ├── approach
│   │   ├── mindset
│   │   └── voice_note
│   ├── practical_guidance
│   ├── category_specific_guidance/
│   ├── safety_and_hazmat
│   └── common_mistakes
├── demo_order/
│   └── demo_final_cleaning/
├── plumbing_electrical/
│   ├── plumbing/
│   └── electrical/
├── crawlspaces/
│   ├── safety/
│   ├── access_and_etiquette/
│   ├── inspection/
│   ├── wet_insulation/
│   ├── air_movement_and_pressure/
│   ├── drying_techniques/
│   └── vapor_barrier/
├── drying_and_monitoring/
│   └── tenting/
├── general_cleaning
├── trash_management_and_logistics
├── final_verification
└── closeout_and_documentation

equipment/
├── dehumidifiers/
├── air_movers/
├── portable_extractors/
├── air_filtration_devices/
├── ulv_foggers/
├── sizing_and_capacity/
├── placement_and_usage/
├── taping_and_routing/
└── performance_monitoring/

project_manager_timeline/
└── days/
    ├── day1
    ├── day2
    ├── monitoring
    └── final