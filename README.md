# resto_kit

**A systematic, job-agnostic personal knowledge base and decision-support system for water damage restoration work, built to be loaded into an AI voice assistant for faster, more consistent field decisions.**

## Purpose

This repo exists to make daily work easier and more consistent. It holds my personal standards, decision logic, equipment rules, and procedures so I can offload mental inventory and focus on the actual job in front of me.

![resto_kit](https://github.com/neuresthetics/resto_kit/blob/main/img/resto_kit_3.png)

## Development

```json

{
  "framework": "resto_kit",
  "meta": {
    "description": {},
    "repository": {},
    "framework_rationale": {
      "description": {},
      "current_state": {},
      "core_value": {},
      "differentiator": {},
      "who_its_for": {},
      "business_case": {}
    },
    "iicrc_alignment": {
      "summary": {},
      "overall_assessment": {},
      "positioning_statement": {},
      "positioning_statement_short": {}
    }
  },
  "index": {
    "AI": {},
    "Response": {},
    "default_mode": {}
  },
  "safety": {},
  "primary_scope": {},
  "language_system": {
    "description": {},
    "levels": {
      "required": {
        "level": {},
        "meaning": {},
        "when_to_use": {}
      },
      "recommended": {
        "level": {},
        "meaning": {},
        "when_to_use": {}
      },
      "optional": {
        "level": {},
        "meaning": {},
        "when_to_use": {}
      }
    },
    "usage_notes": {
      "priority": {},
      "clarity": {},
      "voice_usage": {}
    }
  },
  "modes": {
    "rookie": {
      "name": {},
      "description": {},
      "tone": {},
      "depth": {},
      "when_to_use": {},
      "behavior_rules": {}
    },
    "tech": {
      "name": {},
      "description": {},
      "tone": {},
      "depth": {},
      "when_to_use": {},
      "behavior_rules": {}
    },
    "science_nerd": {
      "name": {},
      "description": {},
      "tone": {},
      "depth": {},
      "when_to_use": {},
      "behavior_rules": {}
    },
    "developer": {
      "name": {},
      "description": {},
      "tone": {},
      "depth": {},
      "when_to_use": {},
      "behavior_rules": {}
    }
  },
  "base_science": {
    "psychrometry": {
      "description": {},
      "core_concepts": {
        "temperature": {
          "term": {},
          "description": {}
        },
        "relative_humidity": {
          "term": {},
          "description": {}
        },
        "grains_per_pound": {
          "term": {},
          "description": {}
        },
        "dew_point": {
          "term": {},
          "description": {}
        },
        "vapor_pressure": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "vapor_pressure_gradient": {
          "description": {}
        },
        "temperature_effect": {
          "description": {}
        },
        "rh_vs_gpp": {
          "description": {}
        }
      },
      "field_implications": {
        "drying_strategy": {
          "description": {}
        },
        "monitoring_value": {
          "description": {}
        },
        "small_spaces": {
          "description": {}
        }
      },
      "common_misunderstandings": {
        "rh_is_enough": {
          "description": {}
        },
        "hot_air_dries_faster": {
          "description": {}
        }
      }
    },
    "moisture_physics": {
      "description": {},
      "core_concepts": {
        "porosity": {
          "term": {},
          "description": {}
        },
        "permeability": {
          "term": {},
          "description": {}
        },
        "wicking": {
          "term": {},
          "description": {}
        },
        "free_water": {
          "term": {},
          "description": {}
        },
        "bound_moisture": {
          "term": {},
          "description": {}
        },
        "absorption_vs_adsorption": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "material_type_matters": {
          "description": {}
        },
        "time_and_penetration": {
          "description": {}
        },
        "vapor_barriers": {
          "description": {}
        }
      },
      "field_implications": {
        "drying_difficulty": {
          "description": {}
        },
        "removal_decisions": {
          "description": {}
        },
        "hidden_moisture_risk": {
          "description": {}
        },
        "vapor_barrier_problems": {
          "description": {}
        }
      },
      "common_misunderstandings": {
        "all_materials_dry_the_same": {
          "description": {}
        },
        "surface_dry_means_dry": {
          "description": {}
        },
        "extraction_fixes_everything": {
          "description": {}
        }
      }
    },
    "water_movement_pathways": {
      "description": {},
      "core_mechanisms": {
        "description": {},
        "bulk_water": {
          "term": {},
          "description": {},
          "field_note": {}
        },
        "capillary_wicking": {
          "term": {},
          "description": {},
          "field_note": {}
        },
        "air_transported": {
          "term": {},
          "description": {},
          "field_note": {}
        },
        "vapor_diffusion": {
          "term": {},
          "description": {},
          "field_note": {}
        }
      },
      "layering_and_drainage": {
        "description": {},
        "drainage_planes": {
          "description": {},
          "field_reality": {}
        },
        "vapor_barriers_as_traps": {
          "description": {},
          "field_note": {}
        },
        "capillary_breaks": {
          "description": {},
          "field_reality": {}
        }
      },
      "horizontal_pathways": {
        "description": {},
        "baseplate_highway": {
          "description": {},
          "field_observation": {}
        },
        "slab_distribution": {
          "description": {},
          "field_observation": {}
        },
        "under_vapor_barrier_flooring": {
          "description": {},
          "field_note": {}
        }
      },
      "vertical_pathways": {
        "description": {},
        "wicking_up_from_foundation": {
          "description": {},
          "field_note": {}
        },
        "dropping_into_lower_levels": {
          "description": {},
          "field_observation": {}
        },
        "wall_cavities": {
          "description": {},
          "field_note": {}
        }
      },
      "high_probability_collection_points": {
        "description": {},
        "items": {}
      },
      "field_implications": {
        "description": {},
        "always_check_adjacent_spaces": {
          "rule": {},
          "why": {}
        },
        "initial_scope_is_almost_always_low": {
          "rule": {},
          "priority": {}
        },
        "concentrated_vs_widespread_entry": {
          "note": {}
        },
        "meter_limitations": {
          "note": {}
        }
      },
      "voice_notes": {}
    },
    "evaporation_principles": {
      "description": {},
      "core_concepts": {
        "evaporation": {
          "term": {},
          "description": {}
        },
        "boundary_layer": {
          "term": {},
          "description": {}
        },
        "vapor_pressure_gradient": {
          "term": {},
          "description": {}
        },
        "air_movement": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "airflow_and_evaporation": {
          "description": {}
        },
        "temperature_and_evaporation": {
          "description": {}
        },
        "humidity_and_evaporation": {
          "description": {}
        },
        "air_movers_vs_dehumidifiers": {
          "description": {}
        }
      },
      "field_implications": {
        "air_mover_placement": {
          "description": {}
        },
        "boundary_layer_disruption": {
          "description": {}
        },
        "small_room_overheating": {
          "description": {}
        },
        "equipment_balance": {
          "description": {}
        }
      },
      "common_misunderstandings": {
        "more_air_is_always_better": {
          "description": {}
        },
        "fans_dry_by_themselves": {
          "description": {}
        },
        "pointing_fans_at_walls": {
          "description": {}
        }
      }
    },
    "material_behavior": {
      "drywall": {
        "description": {}
      },
      "dimensional_lumber": {
        "description": {}
      },
      "hardwood_flooring": {
        "description": {}
      },
      "particle_board_and_mdf": {
        "description": {}
      },
      "concrete_and_slabs": {
        "description": {}
      },
      "insulation": {
        "fiberglass": {
          "description": {}
        },
        "cellulose": {
          "description": {}
        },
        "closed_cell_spray_foam": {
          "description": {}
        }
      },
      "carpet_and_pad": {
        "description": {}
      },
      "lvp_and_sheet_vinyl": {
        "description": {}
      },
      "tile_and_grout": {
        "description": {},
        "grout_readings": {
          "description": {}
        },
        "fiber_cement_false_readings": {
          "description": {}
        },
        "thermal_camera_limitations": {
          "description": {}
        },
        "drying_approach": {
          "description": {}
        },
        "field_note": {
          "description": {}
        }
      },
      "thinset": {
        "description": {},
        "core_behavior": {
          "porosity_and_wicking": {},
          "bonding_issues": {},
          "liner_interaction": {}
        },
        "water_under_liner_scenario": {
          "description": {},
          "drying_difficulty": {}
        },
        "important_caveats": {
          "no_guarantees": {},
          "check_installation": {},
          "risk_vs_cost": {}
        },
        "field_implications": {
          "assessment": {},
          "removal_vs_drying": {},
          "false_security": {}
        },
        "voice_note": {},
        "priority": {}
      },
      "electronics_and_appliances": {
        "description": {}
      },
      "fabrics_and_upholstery": {
        "description": {}
      },
      "documents_and_photos": {
        "description": {}
      },
      "key_relationships": {
        "material_type_drives_decisions": {
          "description": {}
        },
        "time_changes_behavior": {
          "description": {}
        }
      },
      "field_implications": {
        "removal_vs_drying": {
          "description": {}
        },
        "vapor_barriers": {
          "description": {}
        },
        "electronics_caution": {
          "description": {}
        }
      }
    },
    "dry_standards_by_material": {
      "core_principle": {
        "definition": {}
      },
      "wood": {
        "measurement": {},
        "target": {},
        "priority": {}
      },
      "non_wood_materials": {
        "measurement": {},
        "baseline_requirement": {}
      },
      "insulation_rule": {
        "rule": {},
        "exceptions": {},
        "priority": {}
      },
      "drywall_rule": {
        "category1_short_dwell": {},
        "category2_or_3_or_long_dwell": {},
        "priority": {}
      },
      "class4_specialty_drying": {
        "description": {},
        "approach": {},
        "voice_note": {}
      }
    },
    "contamination_science": {
      "description": {},
      "core_concepts": {
        "contamination_level": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "time_and_risk": {
          "description": {}
        }
      },
      "field_implications": {
        "removal_decisions": {
          "description": {}
        },
        "containment_urgency": {
          "description": {}
        },
        "ppe_escalation": {
          "description": {}
        }
      },
      "common_misunderstandings": {
        "clean_water_stays_clean": {
          "description": {}
        },
        "surface_clean_is_enough": {
          "description": {}
        }
      }
    },
    "airflow_and_ventilation": {
      "description": {},
      "core_concepts": {
        "boundary_layer_disruption": {
          "term": {},
          "description": {}
        },
        "directed_airflow": {
          "term": {},
          "description": {}
        },
        "general_circulation": {
          "term": {},
          "description": {}
        },
        "negative_pressure_interaction": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "airflow_and_dehumidification": {
          "description": {}
        },
        "airflow_and_contamination": {
          "description": {}
        },
        "velocity_vs_volume": {
          "description": {}
        },
        "small_space_dynamics": {
          "description": {}
        }
      },
      "field_implications": {
        "air_mover_placement": {
          "description": {}
        },
        "equipment_balance": {
          "description": {}
        },
        "containment_considerations": {
          "description": {}
        },
        "monitoring_airflow": {
          "description": {}
        }
      },
      "common_misunderstandings": {
        "more_fans_is_always_better": {
          "description": {}
        },
        "pointing_fans_directly_at_walls": {
          "description": {}
        },
        "fans_remove_moisture": {
          "description": {}
        }
      }
    },
    "thermodynamics_basics": {
      "description": {},
      "core_concepts": {
        "heat_energy": {
          "term": {},
          "description": {}
        },
        "latent_heat_of_vaporization": {
          "term": {},
          "description": {}
        },
        "air_moisture_capacity": {
          "term": {},
          "description": {}
        },
        "energy_balance": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "temperature_and_drying_rate": {
          "description": {}
        },
        "heat_without_removal": {
          "description": {}
        },
        "small_space_heating": {
          "description": {}
        },
        "evaporative_cooling": {
          "description": {}
        }
      },
      "field_implications": {
        "heat_as_a_tool": {
          "description": {}
        },
        "equipment_interaction": {
          "description": {}
        },
        "small_room_management": {
          "description": {}
        },
        "monitoring_temperature": {
          "description": {}
        }
      },
      "common_misunderstandings": {
        "hotter_is_always_faster": {
          "description": {}
        },
        "dehumidifiers_work_better_when_hot": {
          "description": {}
        },
        "ignoring_temperature": {
          "description": {}
        }
      }
    },
    "corrosion_and_degradation": {
      "description": {},
      "core_concepts": {
        "corrosion": {
          "term": {},
          "description": {}
        },
        "acidic_smoke_residue": {
          "term": {},
          "description": {}
        },
        "hidden_corrosion": {
          "term": {},
          "description": {}
        },
        "electrolytic_corrosion": {
          "term": {},
          "description": {}
        },
        "post_fire_water_synergy": {
          "term": {},
          "description": {}
        },
        "chemical_corrosion": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "smoke_plus_moisture": {
          "description": {}
        },
        "time_and_corrosion": {
          "description": {}
        },
        "electronics_vulnerability": {
          "description": {}
        },
        "hvac_as_distribution_system": {
          "description": {}
        },
        "chemical_cause_of_loss": {
          "description": {}
        }
      },
      "field_implications": {
        "electronics_recommendations": {
          "description": {}
        },
        "hvac_assessment": {
          "description": {}
        },
        "hidden_areas_priority": {
          "description": {}
        },
        "communication_with_customers": {
          "description": {}
        },
        "drying_priority": {
          "description": {}
        },
        "chemical_loss_assessment": {
          "description": {}
        }
      },
      "common_misunderstandings": {
        "if_it_works_it_is_fine": {
          "description": {}
        },
        "cleaning_removes_the_risk": {
          "description": {}
        },
        "only_fire_jobs_have_corrosion": {
          "description": {}
        },
        "surface_dry_means_safe": {
          "description": {}
        },
        "drano_is_just_water": {
          "description": {}
        }
      }
    },
    "mold": {
      "description": {},
      "core_concepts": {
        "conditions_for_growth": {
          "term": {},
          "description": {}
        },
        "microbial_amplification": {
          "term": {},
          "description": {}
        },
        "dwell_time_effect": {
          "term": {},
          "description": {}
        },
        "category_migration": {
          "term": {},
          "description": {}
        },
        "hidden_mold_risk": {
          "term": {},
          "description": {}
        }
      },
      "key_relationships": {
        "time_and_risk": {
          "description": {}
        },
        "temperature_and_growth": {
          "description": {}
        },
        "material_as_food_source": {
          "description": {}
        },
        "aerosolization_risk": {
          "description": {}
        },
        "category_effect_on_risk": {
          "description": {}
        }
      },
      "field_implications": {
        "red_flags_for_hidden_or_active_mold": {
          "description": {},
          "items": {}
        },
        "when_to_treat_as_higher_risk": {
          "description": {},
          "items": {}
        },
        "removal_vs_drying": {
          "description": {}
        },
        "containment_and_controls": {
          "requirements": {},
          "ppe": {}
        },
        "drying_approach_on_mold_jobs": {
          "description": {}
        },
        "field_tips_and_working_rules": {
          "description": {},
          "items": {}
        }
      },
      "common_misunderstandings": {
        "clean_water_stays_clean": {
          "description": {}
        },
        "surface_clean_is_enough": {
          "description": {}
        },
        "no_smell_means_no_contamination": {
          "description": {}
        }
      }
    },
    "materials": {
      "insulation": {
        "rule": {},
        "why": {},
        "exceptions": {},
        "measurement": {},
        "voice_note": {},
        "priority": {},
        "dry_standard_ref": {}
      },
      "drywall": {
        "category1": {
          "approach": {},
          "target": {}
        },
        "category2or3OrLongDwell": {
          "approach": {},
          "cutHeight": {}
        },
        "measurement": {},
        "redFlagsForRemovalEvenOnCat1": {},
        "voice_note": {},
        "priority": {},
        "dry_standard_ref": {}
      },
      "unfinished_wood_framing_subfloor": {
        "target": {},
        "measurement": {},
        "decision_factors": {
          "dryable": {},
          "often_remove_or_treat": {}
        },
        "airflow_note": {},
        "voice_note": {},
        "priority": {}
      },
      "hardwood_flooring": {
        "target": {},
        "practical_notes": {},
        "measurement": {},
        "priority": {}
      },
      "engineered_wood_laminateLVP": {
        "key_issue": {},
        "target": {},
        "approach": {},
        "voice_note": {},
        "priority": {}
      },
      "concrete_slab": {
        "target": {},
        "measurement": {},
        "practical_reality": {},
        "priority": {}
      },
      "carpet_and_pad": {
        "pad": {},
        "carpet": {},
        "target_if_drying": {},
        "priority": {}
      },
      "plaster_lath": {
        "approach": {},
        "target": {},
        "common_on_older_homes": {},
        "priority": {}
      },
      "cabinetry": {
        "particle_board_MDF": {},
        "solid_wood": {},
        "target": {},
        "priority": {}
      },
      "tile_stone_over_substrate": {
        "key_issue": {},
        "target": {},
        "measurement": {},
        "common_decision": {},
        "thinset_liner_interaction": {
          "description": {},
          "under_liner_water": {},
          "assessment_tip": {},
          "voice_note": {}
        },
        "priority": {}
      },
      "contents_electronics_documents_fabrics": {
        "general_rule": {},
        "electronics_appliances": {},
        "documents_photos_books": {},
        "fabrics_clothing_upholstery": {},
        "target": {},
        "priority": {}
      }
    },
    "quick_reference_table": {},
    "working_rules_summary": {},
    "voice_usage_examples": {}
  },
  "equipment": {
    "meta": {
      "description": {},
      "scope": {}
    },
    "general_principles": {},
    "dehumidifiers": {
      "types": {
        "lgr": {},
        "conventional": {},
        "desiccant": {}
      },
      "sizing_rules_of_thumb": {
        "class_1": {},
        "class_2": {},
        "class_3": {},
        "notes": {}
      },
      "placement": {},
      "monitoring_performance": {},
      "common_mistakes": {}
    },
    "air_movers": {
      "types": {
        "axial": {},
        "centrifugal_snail": {}
      },
      "placement_principles": {},
      "quantity_rules": {},
      "common_mistakes": {}
    },
    "portable_extractors": {
      "why_it_matters": {},
      "technique": {},
      "when_especially_important": {},
      "limitations": {}
    },
    "air_filtration_devices": {
      "types": {
        "air_scrubbers": {},
        "negative_air_machines": {}
      },
      "when_to_use": {},
      "setup_tips": {},
      "common_mistakes": {}
    },
    "ulv_foggers": {
      "purpose": {},
      "when_to_use": {},
      "when_not_to_use": {},
      "safety_requirements": {},
      "operation_notes": {}
    },
    "sizing_and_capacity": {
      "quick_assessment_order": {},
      "small_spaces_rule": {},
      "combined_air_volumes": {}
    },
    "placement_and_usage": {
      "core_idea": {},
      "key_tips": {}
    },
    "taping_and_routing": {
      "description": {},
      "required": {},
      "voice_prompt": {}
    },
    "performance_monitoring": {
      "daily_checks": {},
      "temperature_and_humidity": {}
    }
  },
  "job_functions": {
    "description": {},
    "service_contract": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "initial_assessment": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "source_control": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "extraction": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "contents_handling": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "engineering_controls": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "containment": {
      "coreMindset": {},
      "whenToUse": {
        "always": {},
        "airVolume": {},
        "demo": {},
        "isolation": {}
      },
      "recommendedSequence": {},
      "zipper_doors": {
        "single_zipper": {},
        "double_zipper": {},
        "placement_note": {}
      },
      "types": {}
    },
    "selective_demolition": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "remove_vs_dry_criteria": {
        "generally_remove": {},
        "consider_minimal_removal_first": {}
      },
      "chasing_the_water": {
        "description": {},
        "common_hidden_paths": {},
        "field_reality": {},
        "approach": {},
        "mindset": {},
        "voice_note": {},
        "priority": {}
      },
      "practical_guidance": {},
      "category_specific_guidance": {
        "category_1": {},
        "category_2": {},
        "category_3": {}
      },
      "safety_and_hazmat": {},
      "common_mistakes": {},
      "voice_considerations": {}
    },
    "demo_order": {
      "name": {},
      "description": {},
      "steps": {},
      "demo_final_cleaning": {
        "description": {},
        "key_activities": {},
        "alt": {
          "title": {},
          "category": {},
          "conditions": {}
        },
        "critical_decision_points": {},
        "practical_guidance": {},
        "voice_considerations": {},
        "real_world_notes": {}
      }
    },
    "plumbing_electrical": {
      "meta": {
        "description": {},
        "last_updated": {}
      },
      "plumbing": {
        "water_shutoffs": {
          "common_locations": {},
          "field_tips": {}
        },
        "common_issues": {},
        "when_to_involve_a_licensed_plumber": {},
        "old_plumbing_considerations": {
          "galvanized_steel": {},
          "polybutylene_pb": {},
          "copper": {},
          "pex": {}
        },
        "field_tips": {}
      },
      "electrical": {
        "gfci_protection": {
          "rule": {},
          "field_tips": {}
        },
        "common_hazards": {},
        "when_to_involve_a_licensed_electrician": {},
        "old_electrical_systems": {
          "aluminum_wiring": {},
          "knob_and_tube": {}
        },
        "field_tips": {},
        "lockout_tagout": {}
      },
      "combined_considerations": {}
    },
    "crawlspaces": {
      "safety": {
        "atmospheric_testing": {
          "rule": {},
          "required": {},
          "recommended": {},
          "voice_note": {}
        },
        "ppe": {
          "respirator": {
            "approach": {},
            "recommended": {},
            "situational": {},
            "voice_note": {}
          },
          "other": {}
        }
      },
      "access_and_etiquette": {
        "rules": {},
        "manpower": {
          "principle": {},
          "voice_note": {}
        }
      },
      "inspection": {
        "key_things_to_look_for": {},
        "voice_note": {}
      },
      "hot_water_line_breaks": {
        "description": {},
        "why_high_risk": {},
        "inspection_priority": {
          "description": {},
          "check": {}
        },
        "field_implications": {
          "mold_risk": {},
          "air_movement_concern": {},
          "containment_note": {}
        },
        "voice_note": {}
      },
      "wet_insulation": {
        "priority": {},
        "core_rule": {},
        "best_practice": {},
        "field_reality": {},
        "voice_note": {}
      },
      "air_movement_and_pressure": {
        "core_rule": {},
        "key_guidance": {},
        "voice_note": {}
      },
      "drying_techniques": {
        "localized_tenting": {
          "description": {},
          "method": {},
          "voice_note": {}
        },
        "negative_air_setup": {
          "description": {},
          "method": {},
          "voice_note": {}
        }
      },
      "cleaning": {
        "ulv_fogging": {
          "recommendation": {},
          "advantages": {},
          "practical_use": {},
          "voice_note": {}
        }
      },
      "vapor_barrier": {
        "guidance": {},
        "code_requirements": {
          "legal_note": {},
          "key_requirements": {},
          "voice_note": {}
        }
      },
      "ultra_ppe": {
        "when_to_use": {},
        "setup": {},
        "voice_note": {}
      }
    },
    "drying_and_monitoring": {
      "description": {},
      "key_activities": {},
      "tenting": {
        "meta": {
          "description": {},
          "last_updated": {}
        },
        "description": {},
        "when_to_use": {},
        "when_not_to_use": {},
        "setup_guidelines": {
          "basic_requirements": {},
          "best_practices": {}
        },
        "field_tips": {},
        "limitations_and_risks": {},
        "related_techniques": {}
      },
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "general_cleaning": {
      "description": {},
      "core_approach": {},
      "practical_tips": {},
      "voice_note": {}
    },
    "trash_management_and_logistics": {
      "description": {},
      "core_approaches": {
        "clean_as_you_go": {},
        "lightweight_waste": {},
        "batch_then_clean": {}
      },
      "daily_handling": {
        "staging": {},
        "hauling": {}
      },
      "vehicle_loading": {
        "dump_truck": {},
        "cargo_van": {}
      },
      "contaminated_material": {
        "description": {},
        "methods": {},
        "location": {}
      },
      "equipment_decisions": {
        "van": {},
        "dumpster": {},
        "chute": {}
      },
      "key_principles": {}
    },
    "final_verification": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    },
    "closeout_and_documentation": {
      "description": {},
      "key_activities": {},
      "critical_decision_points": {},
      "practical_guidance": {},
      "voice_considerations": {}
    }
  },
  "project_manager_timeline": {
    "dev_note": {},
    "description": {},
    "notes": {},
    "scheduling_meets_reality": {},
    "days": {
      "day1": {
        "name": {},
        "goals": {},
        "key_tasks": {}
      },
      "day2": {
        "name": {},
        "goals": {},
        "key_tasks": {}
      },
      "monitoring": {
        "name": {},
        "goals": {},
        "key_tasks": {},
        "typical_duration": {}
      },
      "final": {
        "name": {},
        "goals": {},
        "key_tasks": {}
      }
    },
    "mindset": {}
  }
}


```