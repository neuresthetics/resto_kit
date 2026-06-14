# resto_kit

**A systematic, job-agnostic personal knowledge base and decision-support system for water damage restoration work, built to be loaded into an AI voice assistant for faster, more consistent field decisions.**

## Purpose

This repo exists to make daily work easier and more consistent. It holds my personal standards, decision logic, equipment rules, and procedures so I can offload mental inventory and focus on the actual job in front of me.

![resto_kit](https://github.com/neuresthetics/resto_kit/blob/main/img/resto_kit_3.jpeg)

## Development

```json

{
  "framework": "str (root identifier)",

  "meta": {
    "description": "str",
    "repository": "str"
  },

  "index": {
    "AI": "str (self-instruction for this map)"
  },

  "safety": "str",

  "primary_scope": "str",

  "language_system": {
    "description": "str",
    "levels": ["required", "recommended", "optional"],
    "usage_notes": ["priority", "clarity", "voice_usage"]
  },

  "modes": {
    "rookie": ["name", "description", "tone", "depth", "when_to_use", "behavior_rules"],
    "tech": ["name", "description", "tone", "depth", "when_to_use", "behavior_rules"],
    "science_nerd": ["name", "description", "tone", "depth", "when_to_use", "behavior_rules"],
    "developer": ["name", "description", "tone", "depth", "when_to_use", "behavior_rules"]
  },

  "base_science": {
    "psychrometry": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "moisture_physics": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "evaporation_principles": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "material_behavior": [
      "description", "drywall", "dimensional_lumber", "hardwood_flooring", "particle_board_and_mdf",
      "concrete_and_slabs", "insulation", "carpet_and_pad", "lvp_and_sheet_vinyl", "tile_and_grout",
      "thinset", "electronics_and_appliances", "fabrics_and_upholstery", "documents_and_photos",
      "key_relationships", "field_implications", "..."
    ],
    "dry_standards_by_material": ["core_principle", "wood", "non_wood_materials", "insulation_rule", "drywall_rule", "class4_specialty_drying"],
    "contamination_science": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "airflow_and_ventilation": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "thermodynamics_basics": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "corrosion_and_degradation": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "mold": ["description", "core_concepts", "key_relationships", "field_implications", "common_misunderstandings"],
    "materials": [
      "insulation", "drywall", "unfinished_wood_framing_subfloor", "hardwood_flooring", "engineered_wood_laminateLVP",
      "concrete_slab", "carpet_and_pad", "plaster_lath", "cabinetry", "tile_stone_over_substrate",
      "contents_electronics_documents_fabrics", "quick_reference_table", "working_rules_summary", "voice_usage_examples"
    ],
    "quick_reference_table": "[list]",
    "working_rules_summary": "[list]",
    "voice_usage_examples": "[list]"
  },

  "equipment": {
    "meta": ["description", "scope"],
    "general_principles": "[list]",
    "dehumidifiers": ["types", "sizing_rules_of_thumb", "placement", "monitoring_performance", "common_mistakes"],
    "air_movers": ["types", "placement_principles", "quantity_rules", "common_mistakes"],
    "portable_extractors": ["why_it_matters", "technique", "when_especially_important", "limitations"],
    "air_filtration_devices": ["types", "when_to_use", "setup_tips", "common_mistakes"],
    "ulv_foggers": ["purpose", "when_to_use", "when_not_to_use", "safety_requirements", "operation_notes"],
    "sizing_and_capacity": ["quick_assessment_order", "small_spaces_rule", "combined_air_volumes"],
    "placement_and_usage": ["core_idea", "key_tips"],
    "taping_and_routing": ["description", "required", "voice_prompt"],
    "performance_monitoring": ["daily_checks", "temperature_and_humidity"]
  },

  "job_functions": {
    "description": "str",
    "service_contract": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "initial_assessment": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "source_control": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "extraction": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "contents_handling": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "engineering_controls": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "containment": ["coreMindset", "whenToUse", "recommendedSequence", "zipper_doors", "types"],
    "selective_demolition": [
      "description", "key_activities", "critical_decision_points", "remove_vs_dry_criteria", "chasing_the_water",
      "practical_guidance", "category_specific_guidance", "safety_and_hazmat", "common_mistakes", "voice_considerations"
    ],
    "demo_order": ["name", "description", "steps", "demo_final_cleaning"],
    "plumbing_electrical": ["meta", "plumbing", "electrical", "combined_considerations"],
    "crawlspaces": [
      "safety", "access_and_etiquette", "inspection", "wet_insulation", "air_movement_and_pressure",
      "drying_techniques", "cleaning", "vapor_barrier", "ultra_ppe"
    ],
    "drying_and_monitoring": ["description", "key_activities", "tenting", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "general_cleaning": ["description", "core_approach", "practical_tips", "voice_note"],
    "trash_management_and_logistics": ["description", "core_approaches", "daily_handling", "vehicle_loading", "contaminated_material", "equipment_decisions", "key_principles"],
    "final_verification": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"],
    "closeout_and_documentation": ["description", "key_activities", "critical_decision_points", "practical_guidance", "voice_considerations"]
  },

  "project_manager_timeline": {
    "dev_note": "str",
    "description": "str",
    "notes": "str",
    "scheduling_meets_reality": "str",
    "days": ["day1", "day2", "monitoring", "final"],
    "mindset": "[list of 6]"
  }
}

```