<!DOCTYPE html>
<!-- saved from url=(0073)https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload -->
<html lang="en" data-color-mode="auto" data-light-theme="light" data-dark-theme="dark" data-a11y-animated-images="system" data-a11y-link-underlines="true" data-turbo-loaded="" class="js-focus-visible" data-js-focus-visible=""><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><style type="text/css">.turbo-progress-bar {
  position: fixed;
  display: block;
  top: 0;
  left: 0;
  height: 3px;
  background: #0076ff;
  z-index: 2147483647;
  transition:
    width 300ms ease-out,
    opacity 150ms 150ms ease-in;
  transform: translate3d(0, 0, 0);
}
</style><style>
:root {
  --fontStack-monospace: "Monaspace Neon", ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace !important;
}
</style>




  
    
  
  
  
  
  
  

<script type="importmap">{"imports":{"react":"https://github.githubassets.com/assets/react-e27d1b3e03961e68.js","react-dom":"https://github.githubassets.com/assets/react-dom-e5fd46a22d5c4058.js","react-dom/client":"https://github.githubassets.com/assets/react-dom-client-1b4a3ee065998cea.js","react-is":"https://github.githubassets.com/assets/react-is-e0b593954b4706d8.js","react-reconciler":"https://github.githubassets.com/assets/react-reconciler-8e99e505c4429605.js","react/compiler-runtime":"https://github.githubassets.com/assets/react-compiler-runtime-4610bd6d3de9c049.js","react/jsx-dev-runtime":"https://github.githubassets.com/assets/react-jsx-dev-runtime-ea55d68667d559e5.js","react/jsx-runtime":"https://github.githubassets.com/assets/react-jsx-runtime-4915cb0f5b3aff04.js","scheduler":"https://github.githubassets.com/assets/scheduler-58b860b049ca307c.js"}}</script>

<meta name="react-import-map" content="react,react-dom,react-dom/client,react-dom/profiling,react-is,react-reconciler,react/compiler-runtime,react/jsx-dev-runtime,react/jsx-runtime,scheduler@777f63f87cd0" data-turbo-track="reload">









  

  <link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/light-5c4e9fc574bf49f3.css"><link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/dark-afff6c53aef9b9d1.css"><link data-color-theme="light_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_high_contrast-fb37c309e0603a69.css"><link data-color-theme="light_colorblind" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_colorblind-0f910d8806d5761b.css"><link data-color-theme="light_colorblind_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_colorblind_high_contrast-a7abd4d4c49ac593.css"><link data-color-theme="light_tritanopia" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_tritanopia-5fc4c4a9cb41e596.css"><link data-color-theme="light_tritanopia_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_tritanopia_high_contrast-ed0cee9214dedabd.css"><link data-color-theme="dark_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_high_contrast-c409873d7987dffa.css"><link data-color-theme="dark_colorblind" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_colorblind-78a2491d538dab5a.css"><link data-color-theme="dark_colorblind_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_colorblind_high_contrast-c26b63d7c532d0a2.css"><link data-color-theme="dark_tritanopia" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_tritanopia-a6f60cea68c08405.css"><link data-color-theme="dark_tritanopia_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_tritanopia_high_contrast-f66faf28b2ea18b6.css"><link data-color-theme="dark_dimmed" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_dimmed-6701f6218c53cf5b.css"><link data-color-theme="dark_dimmed_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_dimmed_high_contrast-7037fa46ae124d97.css">

  <style type="text/css">
    :root {
      --tab-size-preference: 4;
    }

    pre, code {
      tab-size: var(--tab-size-preference);
    }
  </style>

    <link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/primer-primitives-97df7784617ce1ea.css">
    <link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/primer-tailwind-compatible-2c1fd7ca3364e935.css">
    <link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/global-62747e27e61258dc.css">
    <link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/github-b04ca6fccda778e2.css">
    <link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/tailwind-f8e2b544a76f2bd5.css">
  <link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/repository-72bd7d974b5ac1cc.css">

  

  <script type="application/json" id="client-env">{"locale":"en","featureFlags":["actions_caches_react_shell","actions_enable_background_steps","actions_new_hosted_runner_image_select_sizes_and_versions","actions_runners_react_shell","actions_workflow_language_service_allow_case_function","agent_author_search_expansion","agent_author_search_expansion_ui_pulls","alternate_user_config_repo","async_conversion_coverage_enabled","billing_billable_licenses_cost_center_bucket_fix","billing_budget_expiration","billing_cost_center_list_assigned_resources","billing_discount_threshold_notification","ccr_implement_suggestion_refresh","code_quality_enablement_banner_targeting","code_quality_remove_preview","code_view_checks_live_updates","code_view_raf_sticky_lines","codemirror_inp_optimizations","codespaces_prebuild_region_target_update","coding_agent_third_party_model_ui","copilot_agent_snippy","copilot_ahp_tool_call_timing","copilot_api_agentic_issue_marshal_yaml","copilot_automation_repo_mcp_servers","copilot_automations_pagination","copilot_base_model_policy_row","copilot_chat_auto_mode_v2","copilot_chat_clear_model_selection_for_default_change","copilot_chat_disable_model_picker_while_streaming","copilot_chat_early_task_provisioning","copilot_chat_increase_token_padding","copilot_chat_persist_session_drafts","copilot_chat_vision_dotcom_chat_ga_gate","copilot_css_textarea_autosize","copilot_custom_copilots","copilot_custom_copilots_feature_preview","copilot_duplicate_thread","copilot_extensions_removal_on_marketplace","copilot_fix_failed_workflows_all_skus","copilot_hide_hovercard","copilot_immersive_task_hyperlinking","copilot_issue_list_show_more","copilot_mc_cli_resume_any_users_task","copilot_mission_control_agent_merge_fix_ci","copilot_mission_control_agent_merge_resolve_conflicts","copilot_mission_control_awps_batching","copilot_mission_control_early_stop","copilot_mission_control_managed_sandbox_environments","copilot_mission_control_needs_attention","copilot_mission_control_reasoning_effort","copilot_mission_control_sandbox_remote_bypass","copilot_mission_control_task_alive_updates","copilot_mission_control_task_sharing","copilot_org_policy_page_focus_mode","copilot_share_active_subthread","copilot_spaces_ga","copilot_spaces_individual_policies_ga","copilot_swe_agent_authorization_status_ui","copilot_swe_agent_automation_resource_scoped_writes","copilot_swe_agent_discussion_comment_trigger","copilot_swe_agent_discussion_opened_trigger","copilot_swe_agent_discussion_updated_trigger","copilot_swe_agent_hide_model_picker_if_only_auto","copilot_swe_agent_issue_assigned_trigger","copilot_swe_agent_issue_comment_trigger","copilot_swe_agent_issue_labeled_trigger","copilot_swe_agent_pr_comment_model_picker","copilot_swe_agent_pull_request_assigned_trigger","copilot_swe_agent_pull_request_comment_trigger","copilot_swe_agent_pull_request_labeled_trigger","copilot_swe_agent_pull_request_merged_trigger","copilot_swe_agent_pull_request_opened_trigger","copilot_swe_agent_pull_request_ready_for_review_trigger","copilot_swe_agent_pull_request_review_requested_trigger","copilot_swe_agent_pull_request_review_submitted_trigger","copilot_swe_agent_pull_request_synchronize_trigger","copilot_swe_agent_sub_issue_added_trigger","copilot_swe_agent_use_subagents","copilot_task_api_github_rest_style","copilot_task_scoped_alive_channel","copilot_token_based_billing","copilot_unconfigured_is_inherited","copilot_user_can_upgrade_plan_field","copilot_web_integration_cutover","copilot_workbench_sunset_redirect","dashboard_agents_module_auth_token_check","dashboard_indexeddb_caching","datadog_rum","datadog_rum_custom_metrics","fgpat_permissions_selector_redesign","glc_code_quality_repo_settings_workflow_config","hyperspace_2025_logged_out_batch_1","hyperspace_2025_logged_out_batch_2","hyperspace_2025_logged_out_batch_3","in_product_messaging_datadog_monitoring","ipm_ubb_individual_budget_banner","issue_fields_multi_select","issue_inline_avatars","issue_pinned_views","issue_pinned_views_team_vs_personal","issue_relative_time_micro","issue_viewer_paved_path","issues_expanded_file_types","issues_hide_closed_sub_issues","issues_index_query_persistence","issues_lazy_load_comment_box_suggestions","issues_react_chrome_container_query_fix","issues_react_include_bots_in_pickers","issues_react_ui_feedback","labels_archiving","labels_archiving_info","landing_pages_ninetailed","lifecycle_label_name_updates","marketing_cookie_consent_banner","marketing_pages_search_explore_provider","memex_default_issue_create_repository","memex_live_update_hovercard","memex_mwl_filter_field_delimiter","memex_remove_deprecated_type_issue","memex_roadmap_drag_style","merge_queue_restricted_pushers_warning","merge_status_header_feedback","milestone_closed_issues_prioritization","octocaptcha_origin_optimization","pr_sfv_new_diff_fetch","primer_react_css_anchor_positioning","primer_react_merged_forwarded_refs","primer_react_timeline_list_semantics","prs_copilot_app_open_action","prs_css_anchor_positioning","prx_files","pull_request_copilot_attribution_header","pull_request_files_virtualization","pull_request_overview_merge_control","pull_request_overview_panel_edit_description","pull_request_persister","pull_request_stacks_navigation_shortcuts","pull_request_virtualization_image_estimate","pull_request_virtualization_loader_batching","pull_request_virtualization_scroll_compensation","pull_request_virtualization_scroll_intent","quick_search_lazy_suggestions","react_blob_isolate_code_lines","react_blob_overlay","react_blob_ssr_content_visibility","react_data_router_tanstack_allowed","react_logged_out_repository_header","react_query_props_with_key","react_sandbox_future_tanstack","repo_app_turbo","repo_issues_sidebar_layout","repo_pulls_dashboard_declutter","repo_pulls_dashboard_ga","repo_pulls_dashboard_persistence","repo_pulls_dashboard_surface","repos_contributors_limited_default_range","repository_suggester_elastic_search","review_involves_filter","rule_ignored_file_paths","rulesets_actor_list_editor","sample_network_conn_type","security_center_artifact_filters_popover","see_who_reacted","semantic_similarity_duplicate_issue_detection","session_logs_ungroup_reasoning_text","set_sha256_on_repo_creation_form","site_banner_desktop_copilot_app","site_ghca_pixel_mona","site_github_app_ga_page","site_github_app_ga_page_highlight","site_github_app_mobile_native_share","site_global_banner_dev_days_attendee","site_global_nav_spark_models_removed","speculation_rules_ui_service","suggest_custom_property_values_copilot","suppress_automated_browser_vitals","swp_forms_disable_octocaptcha","thread_resolution_reason","track_notifications_settings_usage","ui_route_code_view","ui_route_repos","unified_batch_pr_comments","update_issue_suggestions","viewscreen_sandbox","warn_inaccessible_attachments","webp_support","workstream_plugin_bootstrap"],"login":"joshamanangbao-design","uiComputeCohort":"control","githubDomain":"https://github.com","copilotApiOverrideUrl":"https://api.individual.githubcopilot.com","cmcApiUrl":"https://api.github.com/cmc_internal/api"}</script>
<script type="application/json" id="datadog-rum-config">{"version":1,"applicationId":"851db457-c3a9-463b-b2e5-906d1ef37118","clientToken":"eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaEpJaEpoZFhSb1pXNTBhV05oZEdWa0Jqb0dSVlE9IiwiZXhwIjoiMjAyNi0xMC0xM1QwMTozNjo0MS42OTNaIiwicHVyIjoiYnJvd3Nlcl9zdGF0czpjbGllbnRfdG9rZW4ifX0--060ddff56779b09ed486e49ba3ae032a35d6690c","site":"datadoghq.com","service":"github-ui","env":"production","proxyUrl":"https://api.github.com/_private/browser/rum","sessionSampleRate":100.0,"profilingSampleRate":5.0}</script>






<script crossorigin="anonymous" type="module" src="./README_files/environment-987cd4b44983eb79.js.download" defer="defer"></script>
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/app-runtime.25915bc98fb322a6.module.css">










<script crossorigin="anonymous" type="module" src="./README_files/github-elements-12f2e88695531cc5.js.download" defer="defer"></script>
<script crossorigin="anonymous" type="module" src="./README_files/element-registry-a2875cd7587c3ea7.js.download" defer="defer"></script>

















<script crossorigin="anonymous" type="module" src="./README_files/behaviors-65c75f2f8c345444.js.download" defer="defer"></script>
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/react-core.3792087592bf207a.module.css">
  
  











<script crossorigin="anonymous" type="module" src="./README_files/notifications-subscriptions-menu-fc10d42538bcf032.js.download" defer="defer"></script>
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/primer-react-css.2d881b4d4a503d1c.module.css">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/notifications-subscriptions-menu.12cf33887804858c.module.css">


  



  
  
  
  

    
  


  


    


  
  

  
  

    







  

  




    

  

    

    

      

      

    
    
    

      
  
  


      


      


      
      
      

        


  <meta http-equiv="x-pjax-version" content="f181a6c811c671c26975fe35960a8ec3ad0e8224c28e61438f5b59f38687b38d" data-turbo-track="reload">
  <meta http-equiv="x-pjax-csp-version" content="c4a65e47b0c850e1157ae8e66298070851d7e3b558038de5a3b4ff7a93e630ed" data-turbo-track="reload">
  <meta http-equiv="x-pjax-css-version" content="a80b0545b169f440b929ce2b977c76b6988f014cca6513fb83c5df6581635fb3" data-turbo-track="reload">
  <meta http-equiv="x-pjax-js-version" content="ad5f1c7b32ad2bd571231a2e18652b3014c4651dd68d3452930b0de695787390" data-turbo-track="reload">

  

      

  
  



    

    
  


  


  

  <meta name="release" content="25db80061a7c9ba3e77e33ea9a6846ce29769966" data-turbo-track="reload">
  

  
  
  





  

  <link rel="stylesheet" type="text/css" href="./README_files/kq9.08194f83cc36e56b.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/bv.4fe97623ffc699fa.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/u2l.734a5f51056e244e.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/7b.30a250084f05bcc3.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/yt.bc7126a6df684415.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/t7.ec90f60f1712979d.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/8q.46d7d6bdb11c84c0.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/xjm.aa20c6a53c0f26bb.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/1c.01e55ee7b6c38e82.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/e.83ea0881a382b1d5.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/88.ff314919a1970622.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/yp.4b07ee29a19f8ad1.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/uh.9e8421c844b25f4f.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/2.82ba382e74e3aaf9.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/j.a7dad14b18385aa0.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/h8.cc1668de6549def7.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/4.f1223928c3f8224d.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/u3.a0f5095898a5329c.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/889.5cd0188575b0162c.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/b.bfbf42797cc77bd5.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/wf.0e52a6f5b0f85385.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/1.4751498c13465c06.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/nm.b69726789f50fe74.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/np.4fa1966493ccabc4.module.css" crossorigin="anonymous"><link rel="stylesheet" type="text/css" href="./README_files/sh.4f75f31d4ad49c5d.module.css" crossorigin="anonymous"><link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/editor.2a1947eac6dc374f.module.css"><link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/code-4c5c0895f723f870.css"><script type="module" src="./README_files/editor-65c952ade1f6b995.js.download"></script><script type="module" src="./README_files/repositories-94063eef3d37dfee.js.download"></script><link rel="dns-prefetch" href="https://github.githubassets.com/"><link rel="dns-prefetch" href="https://avatars.githubusercontent.com/"><link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com/"><link rel="dns-prefetch" href="https://user-images.githubusercontent.com/"><link rel="preconnect" href="https://github.githubassets.com/" crossorigin=""><link rel="preconnect" href="https://avatars.githubusercontent.com/"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-e27d1b3e03961e68.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-compiler-runtime-4610bd6d3de9c049.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/scheduler-58b860b049ca307c.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-dom-e5fd46a22d5c4058.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-dom-client-1b4a3ee065998cea.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-is-e0b593954b4706d8.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-jsx-runtime-4915cb0f5b3aff04.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-reconciler-8e99e505c4429605.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/wp-runtime-3b3bf505f0c7e958.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/app-foundation-156c6259e31cc551.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/app-runtime-f6ce38f47c2e1d56.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/fetch-utilities-804a14996977c014.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/ser-fb5d13278eb42203.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/tp-ea613009a991e211.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/catalyst-52ed81112a548e10.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/selector-observer-e8810f64c443fb9b.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/relative-time-element-fe7e72f699fdf493.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/by-9da36843ba9d191d.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/ja9-9a1160b939f2cd52.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/3h-55903cf2303047ad.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/hk-0d35a1220587d888.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/jz5-c964b1a3671f2a92.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/hj-1d800d09e9a8720a.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/j0-1ad12374da9777f2.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/runtime-helpers-5e0b3ae3c4036207.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/aria-live-752acdc868e2da64.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/hotkey-e87ffadced20a3c9.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/react-core-75bc55d9971828b7.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/a9-34620c7b13885011.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/ur-643d2814115561a9.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/4t6-5d0869970ac0aac0.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/pb0-a5c5ec36d311aeef.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/6n-afcf86ccabc4cad2.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/zj-f08c728cf00018aa.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/o6-2a1c68d269710ee9.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/h9a-c6405aa090de0e84.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/vy6-3c3e6e96629c2ce4.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/js-4eb97d5803e657c0.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/g7-baf9e817ae102b01.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/unc-96389cade7bad821.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/nu-65322a6997c6c93c.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/primer-react-7afef75d393cf294.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/op-acddf38478d45ef9.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/ncx-461e4b09f2e67ee5.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/qmp-c7cfba40cf5a93b0.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/j6-148a74299e5a01ab.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/t7l-a52ba56147f77909.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/xs-a0b8c6f4664e6760.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/pd-6a8710840033e042.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/86g-ec28c25ed7d5de06.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/4d-76d8acdf21a33266.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/9e-cece06724bf6ea3b.js"><link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/s1g-d434d712bca59d3a.js"><title>Upload files · joshamanangbao-design/DistanceCalculatorProgram</title><meta name="fetch-nonce" content="v2:9e10e5d5-c294-0699-45fd-63fdda7ed45b"><meta name="current-catalog-service-hash" content="f3abb0cc802f3d7b95fc8762b94bdcb13bf39634c40c357301c4aa1d67a256fb"><link rel="assets" href="https://github.githubassets.com/"><meta name="google-site-verification" content="Apib7-x98H0j5cPqHWwSMm6dNU4GmODRoqxLiDzdx9I"><meta name="octolytics-url" content="https://collector.github.com/github/collect"><meta name="octolytics-actor-id" content="341214825"><meta name="octolytics-actor-login" content="joshamanangbao-design"><meta name="octolytics-actor-hash" content="47f10ba7fcc946d997abaf87128d9841bba66b3e657e0c8f10e8d4cd2d91c400"><meta name="user-login" content="joshamanangbao-design"><link rel="sudo-modal" href="https://github.com/sessions/sudo_modal"><meta name="viewport" content="width=device-width"><meta name="description" content="Contribute to joshamanangbao-design/DistanceCalculatorProgram development by creating an account on GitHub."><link rel="search" type="application/opensearchdescription+xml" href="https://github.com/opensearch.xml" title="GitHub"><link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub"><meta property="fb:app_id" content="1401488693436528"><meta name="apple-itunes-app" content="app-id=1477376905, app-argument=https://github.com/joshamanangbao-design/DistanceCalculatorProgram"><meta name="twitter:image" content="https://opengraph.githubassets.com/8939650064383e502414e8a087687ca0cf69a91b3a7b7be2c654874e13599255/joshamanangbao-design/DistanceCalculatorProgram"><meta name="twitter:site" content="@github"><meta name="twitter:card" content="summary_large_image"><meta name="twitter:title" content="joshamanangbao-design/DistanceCalculatorProgram"><meta name="twitter:description" content="Contribute to joshamanangbao-design/DistanceCalculatorProgram development by creating an account on GitHub."><meta property="og:image" content="https://opengraph.githubassets.com/8939650064383e502414e8a087687ca0cf69a91b3a7b7be2c654874e13599255/joshamanangbao-design/DistanceCalculatorProgram"><meta property="og:image:alt" content="Contribute to joshamanangbao-design/DistanceCalculatorProgram development by creating an account on GitHub."><meta property="og:image:width" content="1200"><meta property="og:image:height" content="600"><meta property="og:site_name" content="GitHub"><meta property="og:type" content="object"><meta property="og:title" content="joshamanangbao-design/DistanceCalculatorProgram"><meta property="og:url" content="https://github.com/joshamanangbao-design/DistanceCalculatorProgram"><meta property="og:description" content="Contribute to joshamanangbao-design/DistanceCalculatorProgram development by creating an account on GitHub."><link rel="shared-web-socket" href="wss://alive.github.com/_sockets/u/341214825/ws?session=eyJ2IjoiVjMiLCJ1IjozNDEyMTQ4MjUsInMiOjIzNDk3ODM0ODIsImMiOjM2MjE4NTM2NDgsInQiOjE3OTE3NjkwMDF9--12df65d64f46bcccc2d20a1d2bbcab35e7adcf47cd336582c4b27380ea88a7aa" data-refresh-url="/_alive" data-session-id="fc89e4cde08f8931248304a5e0d8e21634e90c1294aef8f6339b9193b85c2873"><meta name="hostname" content="github.com"><meta name="keyboard-shortcuts-preference" content="all"><meta name="hovercards-preference" content="true"><meta name="announcement-preference-hovercard" content="true"><meta name="expected-hostname" content="github.com"><meta name="go-import" content="github.com/joshamanangbao-design/DistanceCalculatorProgram git https://github.com/joshamanangbao-design/DistanceCalculatorProgram.git"><meta name="octolytics-dimension-user_id" content="341214825"><meta name="octolytics-dimension-user_login" content="joshamanangbao-design"><meta name="octolytics-dimension-repository_id" content="1414928862"><meta name="octolytics-dimension-repository_nwo" content="joshamanangbao-design/DistanceCalculatorProgram"><meta name="octolytics-dimension-repository_public" content="true"><meta name="octolytics-dimension-repository_is_fork" content="false"><meta name="octolytics-dimension-repository_network_root_id" content="1414928862"><meta name="octolytics-dimension-repository_network_root_nwo" content="joshamanangbao-design/DistanceCalculatorProgram"><meta name="current-repo-nwo" content="joshamanangbao-design/DistanceCalculatorProgram"><meta name="turbo-body-classes" content="logged-in env-production page-responsive text-rendering-optimize-speed"><meta name="disable-turbo" content="false"><meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats"><meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors"><meta name="ui-target" content="full"><link rel="mask-icon" href="https://github.githubassets.com/assets/pinned-octocat-093da3e6fa40.svg" color="#000000"><link rel="alternate icon" class="js-site-favicon" type="image/png" href="https://github.githubassets.com/favicons/favicon.png"><link rel="icon" class="js-site-favicon" type="image/svg+xml" href="https://github.githubassets.com/favicons/favicon.svg" data-base-href="https://github.githubassets.com/favicons/favicon"><meta name="theme-color" content="#1e2327"><meta name="color-scheme" content="light dark"><link rel="manifest" href="https://github.com/manifest.json" crossorigin="use-credentials"><meta name="react-profiling" content="0" data-turbo-transient=""><meta name="route-pattern" content="/:user_id/:repository/upload(/:name)(/*path)(.:format)" data-turbo-transient=""><meta name="route-controller" content="repository_uploads" data-turbo-transient=""><meta name="route-action" content="index" data-turbo-transient=""><meta name="selected-link" value="repo_source" data-turbo-transient=""><meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/repository_uploads/index" data-turbo-transient=""><meta name="request-id" content="C4B0:3790C9:7F9886:D186AC:6ACC39AB" data-turbo-transient=""><meta name="html-safe-nonce" content="b65626e2f228f2a59e579cfbe15aeb8b5ac4aa16c7d1485f3f770a54e0666505" data-turbo-transient=""><meta name="visitor-payload" content="eyJyZWZlcnJlciI6Imh0dHBzOi8vZ2l0aHViLmNvbS9qb3NoYW1hbmFuZ2Jhby1kZXNpZ24vRGlzdGFuY2VDYWxjdWxhdG9yUHJvZ3JhbSIsInJlcXVlc3RfaWQiOiJDNEIwOjM3OTBDOTo3Rjk4ODY6RDE4NkFDOjZBQ0MzOUFCIiwidmlzaXRvcl9pZCI6Ijg4OTk4NzMyOTgwMjU1NTkxNzAiLCJyZWdpb25fZWRnZSI6InNvdXRoZWFzdGFzaWEiLCJyZWdpb25fcmVuZGVyIjoiaWFkIn0=" data-turbo-transient=""><meta name="visitor-hmac" content="0d09ca20c785b62aeebbe781fa2413a43c5d2be7ab5dc82802fe6a13e0172a8f" data-turbo-transient=""><meta name="github-keyboard-shortcuts" content="repository,copilot" data-turbo-transient=""><meta name="hovercard-subject-tag" content="repository:1414928862" data-turbo-transient=""><meta name="turbo-cache-control" content="no-preview" data-turbo-transient=""></head>

  <body class="logged-in env-production page-responsive text-rendering-optimize-speed" style="word-wrap: break-word;">
    <div data-turbo-body="" class="logged-in env-production page-responsive text-rendering-optimize-speed" style="word-wrap: break-word;">
      <div id="__primerPortalRoot__" style="z-index: 1000; position: absolute; width: 100%;" data-turbo-permanent=""></div>
      

    <div class="position-relative header-wrapper js-header-wrapper ">
      <a href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload#start-of-content" data-skip-target-assigned="false" class="tmp-p-3 color-bg-accent-emphasis color-fg-on-emphasis show-on-focus js-skip-to-content">Skip to content</a>

      <span data-view-component="true" class="progress-pjax-loader Progress position-fixed width-full">
    <span style="width: 0%;" data-view-component="true" class="Progress-item progress-pjax-loader-bar left-0 top-0 color-bg-accent-emphasis"></span>
</span>      
      <link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/19-c660652a0a1639be.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/keyboard-shortcuts-dialog-f0e2b9ee3556a2db.js" fetchpriority="low">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/primer-react-css.2d881b4d4a503d1c.module.css">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/keyboard-shortcuts-dialog.6f812a1fa5f96270.module.css">

<react-partial partial-name="keyboard-shortcuts-dialog" data-ssr="false" data-attempted-ssr="false" data-react-profiling="false" data-catalyst="" class="loaded">
  
  <script type="application/json" data-target="react-partial.embeddedData">{"props":{"docsUrl":"https://docs.github.com/get-started/accessibility/keyboard-shortcuts"}}</script>
  <div data-target="react-partial.reactRoot"><div class="d-none"></div></div>
</react-partial>





      

          <link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/app-install-banner-partial-e223ad8be3b21796.js" fetchpriority="low">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/primer-react-css.2d881b4d4a503d1c.module.css">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/app-install-banner-partial.05cc6d269f104b45.module.css">

<react-partial partial-name="app-install-banner-partial" data-ssr="false" data-attempted-ssr="false" data-react-profiling="false" data-catalyst="" class="loaded">
  
  <script type="application/json" data-target="react-partial.embeddedData">{"props":{}}</script>
  <div data-target="react-partial.reactRoot"></div>
</react-partial>


          

                  <link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/y5-ed17e73b4c0bd15e.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/n4-be595475cdbf7d4b.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/j8-23a3c5ff8eef412d.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/ym-6bc2c9bf8112c038.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/sk2-8deeef9351be3911.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/ni-3e194d222c7770bf.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/iq-6d4ecf6d2fb6993c.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/p2-7d8e7cee5b46cb45.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/lf-910ef220ce85c660.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/7x-71d30cb240cd901f.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/wwk-ad869086822937b1.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/a1-9f79841ecac1da8e.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/r6s-9039f5619230a653.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/pj-87629cb5389d7663.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/wzg-884fd1eebdfacfca.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/5f-64f8e7d5bcbd4787.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/z5-b53a93078d026f1e.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/8h-cef26f68c1331011.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/fq-3ce13a77e863807a.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/a7-8b99902a4bb5fa55.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/xfx-c82d8352413aea0a.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/j4-b3a9e87fa7878a98.js" fetchpriority="low">
<link crossorigin="anonymous" rel="modulepreload" href="https://github.githubassets.com/assets/global-nav-bar-76660df7d2e2bdb7.js" fetchpriority="low">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/primer-react-css.2d881b4d4a503d1c.module.css">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/pj.75627bfeb9ceb1da.module.css">
<link crossorigin="anonymous" media="all" rel="stylesheet" href="./README_files/global-nav-bar.e1686f2377cce6ef.module.css">

<react-partial partial-name="global-nav-bar" data-ssr="true" data-attempted-ssr="true" data-react-profiling="false" data-catalyst="" class="loaded">
  
  <script type="application/json" data-target="react-partial.embeddedData">{"props":{"contextRegion":{"crumbs":[{"crumb_type":"user","label":"joshamanangbao-design","is_root":false,"href":"/joshamanangbao-design"},{"crumb_type":"repository","label":"DistanceCalculatorProgram","is_root":false,"href":"/joshamanangbao-design/DistanceCalculatorProgram"}],"localNavigation":[{"id":"code","icon":"code","label":"Code","href":"/joshamanangbao-design/DistanceCalculatorProgram","selectedLinks":["repo_source","repo_downloads","repo_commits","repo_releases","repo_tags","repo_branches","repo_packages","repo_deployments","repo_attestations"],"popoverTarget":false,"commandId":"repositories:go-to-code","reactNav":{"appTarget":"code-view","anchor":"code-view-repo-link"},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"issues","icon":"issue-opened","label":"Issues","href":"/joshamanangbao-design/DistanceCalculatorProgram/issues","selectedLinks":["repo_issues","repo_labels","repo_milestones"],"count":0,"popoverTarget":false,"commandId":"repositories:go-to-issues","reactNav":{"appTarget":"repo","anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"pull-requests","icon":"git-pull-request","label":"Pull requests","href":"/joshamanangbao-design/DistanceCalculatorProgram/pulls","selectedLinks":["repo_pulls","checks"],"count":0,"popoverTarget":false,"commandId":"repositories:go-to-pull-requests","reactNav":{"appTarget":"repo","anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"actions","icon":"play","label":"Actions","href":"/joshamanangbao-design/DistanceCalculatorProgram/actions","selectedLinks":["repo_actions"],"popoverTarget":false,"commandId":"repositories:go-to-actions","reactNav":{"appTarget":"actions-workflows","anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"projects","icon":"table","label":"Projects","href":"/joshamanangbao-design/DistanceCalculatorProgram/projects","selectedLinks":["repo_projects","new_repo_project","repo_project"],"popoverTarget":false,"commandId":"repositories:go-to-projects","reactNav":{"appTarget":"repo","anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"wiki","icon":"book","label":"Wiki","href":"/joshamanangbao-design/DistanceCalculatorProgram/wiki","selectedLinks":["repo_wiki"],"popoverTarget":false,"commandId":"repositories:go-to-wiki","reactNav":{"appTarget":null,"anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"security-and-quality","icon":"shield","label":"Security and quality","href":"/joshamanangbao-design/DistanceCalculatorProgram/security","selectedLinks":["security","overview","alerts","policy","token_scanning","code_scanning"],"count":0,"popoverTarget":false,"commandId":"repositories:go-to-security","reactNav":{"appTarget":null,"anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"insights","icon":"graph","label":"Insights","href":"/joshamanangbao-design/DistanceCalculatorProgram/pulse","selectedLinks":["repo_graphs","repo_contributors","dependency_graph","dependabot_updates","pulse","people","community"],"popoverTarget":false,"commandId":"repositories:go-to-insights","reactNav":{"appTarget":null,"anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}},{"id":"settings","icon":"gear","label":"Settings","href":"/joshamanangbao-design/DistanceCalculatorProgram/settings","selectedLinks":["code_review_limits","code_quality","codespaces_repository_settings","collaborators","custom_tabs","hooks","integration_installations","interaction_limits","issue_template_editor","key_links_settings","license_policy","notifications","repo_announcements","repo_branch_settings","repo_custom_properties","repo_keys_settings","repo_pages_settings","repo_protected_tags_settings","repo_rule_insights","repo_rule_insights_dashboard","repo_rules_bypass_requests","repo_rulesets","repo_settings_copilot_coding_guidelines","repo_settings_copilot_content_exclusion","repo_settings_copilot_dreams","repo_settings_copilot_internet_access","repo_settings_copilot_mcp","repo_settings_copilot_swe_agent","repo_settings","repo_suggestions_settings","reported_content","repository_actions_settings_add_new_runner","repository_actions_settings_general","repository_actions_settings_runner_details","repository_actions_settings_runners","repository_actions_settings","repository_actions_settings_policies","repository_actions_settings_policies_insights","repository_actions_settings_oidc_configuration","repository_drives_settings","repository_environments","role_details","secrets_settings_actions","secrets_settings_agents","secrets_settings_codespaces","secrets_settings_dependabot","secrets","security_analysis","security_products"],"popoverTarget":false,"commandId":"repositories:go-to-settings","reactNav":{"appTarget":null,"anchor":null},"turboNav":{"frame":"repo-content-turbo-frame"}}],"localNavigationUpdateChannel":"eyJjIjoicmVwbzoxNDE0OTI4ODYyOnVzZXI6MzQxMjE0ODI1OnNldHRpbmdzIiwidCI6MTc5MTc2OTAwMX0=--444ef80270e9b32bcd629fa34f93154db8cfb90e7bb602c02ce8f5b2ba1ea1f0","selectedLink":null,"currentPath":"/joshamanangbao-design/DistanceCalculatorProgram"},"owner":{"login":"joshamanangbao-design","name":null,"avatarUrl":"https://avatars.githubusercontent.com/u/341214825?v=4"},"headerLogo":{"href":"/","aria-label":"Homepage "},"notifications":{"indicatorMode":"none","websocketChannel":"eyJjIjoibm90aWZpY2F0aW9uLWNoYW5nZWQ6MzQxMjE0ODI1IiwidCI6MTc5MTc2OTAwMX0=--9ba0cce63039293c3a6e04a72a7cace77853c6eb9060dc5a4976e83f9d47c805","fetchIndicatorSrc":"/notifications/indicator","fetchIndicatorEnabled":true},"issues":{"href":"/issues"},"pulls":{"href":"/pulls"},"contributedRepos":{"href":"/repos"},"copilot":{"show":true,"showAgentsButton":false,"showRelaunchAnnouncement":false,"copilotChatUrl":"/github-copilot/chat?skip_anchor=true","copilotApiUrl":"https://api.individual.githubcopilot.com"},"search":{"show":true,"showCommandPalette":false,"isSearchPage":false,"isJumpToSearch":false,"searchContext":{"scope":"repo:joshamanangbao-design/DistanceCalculatorProgram","current_repo_name":"DistanceCalculatorProgram","current_repo_nwo":"joshamanangbao-design/DistanceCalculatorProgram","user_id":"joshamanangbao-design"}},"commandPalette":null,"enterpriseBar":{"show":false},"globalTransactionalMessage":[],"payloadsUrl":"/_global-navigation/payloads.json?can_toggle_site_admin_and_employee_status=0\u0026is_admin_mode_on=0\u0026is_ui_opted_out=0\u0026show_ui_opt_out=0\u0026v=7","contextRegionUrl":"/_global-navigation/context-region.json"}}</script>
  <div data-target="react-partial.reactRoot"><link rel="preload" as="image" href="./README_files/341214825"><header aria-label="Global navigation menu" data-component="Stack" class="GlobalNav styles-module__appHeader__YzYWk prc-Stack-Stack-UQ9k6" data-gap="none" data-direction="vertical" data-align="stretch" data-wrap="nowrap" data-justify="start" data-padding="none"><div data-component="Stack" class="prc-Stack-Stack-UQ9k6" data-direction="horizontal" data-align="center" data-wrap="nowrap" data-justify="center" data-padding="none"><div data-testid="top-nav-left" data-component="Stack" class="styles-module__left__Fylw7 styles-module__withLocalNavigation__rjTJ_ prc-Stack-Stack-UQ9k6" data-gap="condensed" data-direction="horizontal" data-align="stretch" data-wrap="nowrap" data-justify="start" data-padding="normal"><div data-loading-wrapper="true"><button data-component="IconButton" type="button" aria-haspopup="dialog" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_1b9_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-three-bars" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M1 2.75A.75.75 0 0 1 1.75 2h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 2.75Zm0 5A.75.75 0 0 1 1.75 7h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 7.75ZM1.75 12h12.5a.75.75 0 0 1 0 1.5H1.75a.75.75 0 0 1 0-1.5Z"></path></svg></button></div><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" id="_R_1b9_" popover="auto">Open menu</span><div class="d-none"></div><a data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderHome__nkA_U prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_1j9_" href="https://github.com/" data-discover="true"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-mark-github" viewBox="0 0 24 24" width="32" height="32" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M10.226 17.284c-2.965-.36-5.054-2.493-5.054-5.256 0-1.123.404-2.336 1.078-3.144-.292-.741-.247-2.314.09-2.965.898-.112 2.111.36 2.83 1.01.853-.269 1.752-.404 2.853-.404 1.1 0 1.999.135 2.807.382.696-.629 1.932-1.1 2.83-.988.315.606.36 2.179.067 2.942.72.854 1.101 2 1.101 3.167 0 2.763-2.089 4.852-5.098 5.234.763.494 1.28 1.572 1.28 2.807v2.336c0 .674.561 1.056 1.235.786 4.066-1.55 7.255-5.615 7.255-10.646C23.5 6.188 18.334 1 11.978 1 5.62 1 .5 6.188.5 12.545c0 4.986 3.167 9.12 7.435 10.669.606.225 1.19-.18 1.19-.786V20.63a2.9 2.9 0 0 1-1.078.224c-1.483 0-2.359-.808-2.987-2.313-.247-.607-.517-.966-1.034-1.033-.27-.023-.359-.135-.359-.27 0-.27.45-.471.898-.471.652 0 1.213.404 1.797 1.235.45.651.921.943 1.483.943.561 0 .92-.202 1.437-.719.382-.381.674-.718.944-.943"></path></svg></a><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" popover="auto"><span id="_R_1j9_">Homepage <span class="prc-src-InternalVisuallyHidden-2YaI6">(<!-- -->g then d<!-- -->)</span></span><span class="prc-TooltipV2-KeybindingHintContainer-Ymj-3 prc-TooltipV2-HasTextBefore-fdOXj" aria-hidden="true" data-component="Tooltip.KeybindingHintContainer"><kbd class="prc-KeybindingHint-KeybindingHint-qpYIs prc-Text-Text-9mHv3" data-component="KeybindingHint" data-testid="keybinding-hint"><span class="prc-components-Chord-DdhWN prc-components-ChordOnEmphasis-O-4BS prc-components-ChordSmall-c-P-x prc-Text-Text-9mHv3" data-component="Text" data-kbd-chord="true"> <span class="prc-src-InternalVisuallyHidden-2YaI6">g</span><span aria-hidden="true">G</span></span><span class="prc-src-InternalVisuallyHidden-2YaI6">then</span> <span class="prc-components-Chord-DdhWN prc-components-ChordOnEmphasis-O-4BS prc-components-ChordSmall-c-P-x prc-Text-Text-9mHv3" data-component="Text" data-kbd-chord="true"> <span class="prc-src-InternalVisuallyHidden-2YaI6">d</span><span aria-hidden="true">D</span></span></kbd></span></span><div class="d-none"></div></div><div data-testid="top-nav-center" data-component="Stack" class="styles-module__center__R3QRv styles-module__withLocalNavigation__rjTJ_ prc-Stack-Stack-UQ9k6" data-gap="condensed" data-direction="horizontal" data-align="stretch" data-wrap="nowrap" data-justify="start" data-padding="normal"><nav class="styles-module__contextRegion__VbSp2 prc-Breadcrumbs-BreadcrumbsBase-3Gb-B" aria-label="Breadcrumbs" data-overflow="menu" data-variant="normal" data-component="Breadcrumbs"><ol class="prc-Breadcrumbs-BreadcrumbsList-BKjpe"><li class="prc-Breadcrumbs-ItemWrapper-k0NLn"><a class="styles-module__contextCrumb__IzGIq prc-Breadcrumbs-Item-jcraJ" data-component="Breadcrumbs.Item" href="https://github.com/joshamanangbao-design" data-discover="true"><span class="">joshamanangbao-design</span></a></li><li class="prc-Breadcrumbs-ItemWrapper-k0NLn"><a class="styles-module__contextCrumb__IzGIq styles-module__contextCrumbLast__tI2e3 styles-module__repoPickerCrumb__dk81Q prc-Breadcrumbs-Item-jcraJ" data-component="Breadcrumbs.Item" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram" data-discover="true">DistanceCalculatorProgram</a><div class="d-none"></div><button data-component="IconButton" type="button" aria-haspopup="true" aria-expanded="false" tabindex="0" class="prc-Button-ButtonBase-9n-Xk styles-module__contextCrumb__IzGIq styles-module__repoPickerDropdownButton__WjHYX prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="small" data-variant="invisible" aria-labelledby="_R_3eqd9_" id="_R_eqd9_" style="anchor-name: --anchored-overlay-anchor-_R_eqd9H1_;"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-triangle-down" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" popover="auto"><span id="_R_3eqd9_">Switch repository<span class="prc-src-InternalVisuallyHidden-2YaI6">(<!-- -->alt shift r<!-- -->)</span></span><span class="prc-TooltipV2-KeybindingHintContainer-Ymj-3 prc-TooltipV2-HasTextBefore-fdOXj" aria-hidden="true" data-component="Tooltip.KeybindingHintContainer"><kbd class="prc-KeybindingHint-KeybindingHint-qpYIs prc-Text-Text-9mHv3" data-component="KeybindingHint" data-testid="keybinding-hint"><span class="prc-components-Chord-DdhWN prc-components-ChordOnEmphasis-O-4BS prc-components-ChordSmall-c-P-x prc-Text-Text-9mHv3" data-component="Text" data-kbd-chord="true"> <span class="prc-src-InternalVisuallyHidden-2YaI6">alt</span><span aria-hidden="true">Alt</span> <span class="prc-src-InternalVisuallyHidden-2YaI6">shift</span><span aria-hidden="true">⇧</span> <span class="prc-src-InternalVisuallyHidden-2YaI6">r</span><span aria-hidden="true">R</span></span></kbd></span></span></li></ol></nav><div class="Search-module__searchButtonGroup__aetw5 prc-ButtonGroup-ButtonGroup-vFUrY" data-component="ButtonGroup"><div class="prc-ButtonGroup-Item-PqvDl"><button data-component="Button" type="button" aria-label="Open quick search dialog, type / to search" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ Search-module__searchButton__aiE0a" data-loading="false" data-size="medium" data-variant="invisible"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="leadingVisual" class="prc-Button-Visual-YNt2F prc-Button-LeadingVisual-UySKu prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-search" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M10.68 11.74a6 6 0 0 1-7.922-8.982 6 6 0 0 1 8.982 7.922l3.04 3.04a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215ZM11.5 7a4.499 4.499 0 1 0-8.997 0A4.499 4.499 0 0 0 11.5 7Z"></path></svg></span><span data-component="text" class="prc-Button-Label-FWkx3"><span class="Search-module__placeholder__p9hbG Search-module__text__veSYi Search-module__value__TFoak">Type <kbd class="Search-module__kbd__WCskr">/</kbd> to search</span></span></span></button></div><div class="prc-ButtonGroup-Item-PqvDl"></div></div><button data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ Search-module__smallSearchButton___8Gvn prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_al9_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-search" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M10.68 11.74a6 6 0 0 1-7.922-8.982 6 6 0 0 1 8.982 7.922l3.04 3.04a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215ZM11.5 7a4.499 4.499 0 1 0-8.997 0A4.499 4.499 0 0 0 11.5 7Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" popover="auto"><span id="_R_al9_">Open quick search dialog, type / to search<span class="prc-src-InternalVisuallyHidden-2YaI6">(<!-- -->forward slash<!-- -->)</span></span><span class="prc-TooltipV2-KeybindingHintContainer-Ymj-3 prc-TooltipV2-HasTextBefore-fdOXj" aria-hidden="true" data-component="Tooltip.KeybindingHintContainer"><kbd class="prc-KeybindingHint-KeybindingHint-qpYIs prc-Text-Text-9mHv3" data-component="KeybindingHint" data-testid="keybinding-hint"><span class="prc-components-Chord-DdhWN prc-components-ChordOnEmphasis-O-4BS prc-components-ChordSmall-c-P-x prc-Text-Text-9mHv3" data-component="Text" data-kbd-chord="true"> <span class="prc-src-InternalVisuallyHidden-2YaI6">forward slash</span><span aria-hidden="true">/</span></span></kbd></span></span><div class="d-none"></div></div><div data-testid="top-nav-right" data-component="Stack" class="styles-module__right__mlBQg styles-module__withLocalNavigation__rjTJ_ styles-module__rightWithResponsiveCreateButton__SKn2W prc-Stack-Stack-UQ9k6" data-gap="condensed" data-direction="horizontal" data-align="center" data-wrap="nowrap" data-justify="start" data-padding="normal"><div data-testid="top-bar-actions" data-component="Stack" class="prc-Stack-Stack-UQ9k6" data-gap="condensed" data-direction="horizontal" data-align="center" data-wrap="nowrap" data-justify="start" data-padding="none"><div class="hide-sm hide-md"><div class="CopilotItems-module__Wrapper__BFG9q"><div class="prc-ButtonGroup-ButtonGroup-vFUrY" data-component="ButtonGroup"><div class="prc-ButtonGroup-Item-PqvDl"><a data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_1aif9_" href="https://github.com/copilot" data-discover="true"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-copilot" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M7.998 15.035c-4.562 0-7.873-2.914-7.998-3.749V9.338c.085-.628.677-1.686 1.588-2.065.013-.07.024-.143.036-.218.029-.183.06-.384.126-.612-.201-.508-.254-1.084-.254-1.656 0-.87.128-1.769.693-2.484.579-.733 1.494-1.124 2.724-1.261 1.206-.134 2.262.034 2.944.765.05.053.096.108.139.165.044-.057.094-.112.143-.165.682-.731 1.738-.899 2.944-.765 1.23.137 2.145.528 2.724 1.261.566.715.693 1.614.693 2.484 0 .572-.053 1.148-.254 1.656.066.228.098.429.126.612.012.076.024.148.037.218.924.385 1.522 1.471 1.591 2.095v1.872c0 .766-3.351 3.795-8.002 3.795Zm0-1.485c2.28 0 4.584-1.11 5.002-1.433V7.862l-.023-.116c-.49.21-1.075.291-1.727.291-1.146 0-2.059-.327-2.71-.991A3.222 3.222 0 0 1 8 6.303a3.24 3.24 0 0 1-.544.743c-.65.664-1.563.991-2.71.991-.652 0-1.236-.081-1.727-.291l-.023.116v4.255c.419.323 2.722 1.433 5.002 1.433ZM6.762 2.83c-.193-.206-.637-.413-1.682-.297-1.019.113-1.479.404-1.713.7-.247.312-.369.789-.369 1.554 0 .793.129 1.171.308 1.371.162.181.519.379 1.442.379.853 0 1.339-.235 1.638-.54.315-.322.527-.827.617-1.553.117-.935-.037-1.395-.241-1.614Zm4.155-.297c-1.044-.116-1.488.091-1.681.297-.204.219-.359.679-.242 1.614.091.726.303 1.231.618 1.553.299.305.784.54 1.638.54.922 0 1.28-.198 1.442-.379.179-.2.308-.578.308-1.371 0-.765-.123-1.242-.37-1.554-.233-.296-.693-.587-1.713-.7Z"></path><path d="M6.25 9.037a.75.75 0 0 1 .75.75v1.501a.75.75 0 0 1-1.5 0V9.787a.75.75 0 0 1 .75-.75Zm4.25.75v1.501a.75.75 0 0 1-1.5 0V9.787a.75.75 0 0 1 1.5 0Z"></path></svg></a><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" id="_R_1aif9_" popover="auto">Chat with Copilot</span></div><div class="prc-ButtonGroup-Item-PqvDl"><div class="d-none"></div><button data-component="ActionMenu.Button" type="button" aria-label="Open Copilot…" aria-haspopup="true" aria-expanded="false" tabindex="0" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ CopilotItems-module__CopilotMenu__DVdfE" data-loading="false" data-size="medium" data-variant="invisible" id="_R_2iif9_" style="anchor-name: --anchored-overlay-anchor-_R_eiif9H1_;"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="leadingVisual" class="prc-Button-Visual-YNt2F prc-Button-LeadingVisual-UySKu prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-copilot" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M7.998 15.035c-4.562 0-7.873-2.914-7.998-3.749V9.338c.085-.628.677-1.686 1.588-2.065.013-.07.024-.143.036-.218.029-.183.06-.384.126-.612-.201-.508-.254-1.084-.254-1.656 0-.87.128-1.769.693-2.484.579-.733 1.494-1.124 2.724-1.261 1.206-.134 2.262.034 2.944.765.05.053.096.108.139.165.044-.057.094-.112.143-.165.682-.731 1.738-.899 2.944-.765 1.23.137 2.145.528 2.724 1.261.566.715.693 1.614.693 2.484 0 .572-.053 1.148-.254 1.656.066.228.098.429.126.612.012.076.024.148.037.218.924.385 1.522 1.471 1.591 2.095v1.872c0 .766-3.351 3.795-8.002 3.795Zm0-1.485c2.28 0 4.584-1.11 5.002-1.433V7.862l-.023-.116c-.49.21-1.075.291-1.727.291-1.146 0-2.059-.327-2.71-.991A3.222 3.222 0 0 1 8 6.303a3.24 3.24 0 0 1-.544.743c-.65.664-1.563.991-2.71.991-.652 0-1.236-.081-1.727-.291l-.023.116v4.255c.419.323 2.722 1.433 5.002 1.433ZM6.762 2.83c-.193-.206-.637-.413-1.682-.297-1.019.113-1.479.404-1.713.7-.247.312-.369.789-.369 1.554 0 .793.129 1.171.308 1.371.162.181.519.379 1.442.379.853 0 1.339-.235 1.638-.54.315-.322.527-.827.617-1.553.117-.935-.037-1.395-.241-1.614Zm4.155-.297c-1.044-.116-1.488.091-1.681.297-.204.219-.359.679-.242 1.614.091.726.303 1.231.618 1.553.299.305.784.54 1.638.54.922 0 1.28-.198 1.442-.379.179-.2.308-.578.308-1.371 0-.765-.123-1.242-.37-1.554-.233-.296-.693-.587-1.713-.7Z"></path><path d="M6.25 9.037a.75.75 0 0 1 .75.75v1.501a.75.75 0 0 1-1.5 0V9.787a.75.75 0 0 1 .75-.75Zm4.25.75v1.501a.75.75 0 0 1-1.5 0V9.787a.75.75 0 0 1 1.5 0Z"></path></svg></span></span><span data-component="trailingAction" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-triangle-down" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg></span></button></div></div></div></div><div class="CopilotImmersiveEmbedded-module__CopilotChatContainer__Hqz45" data-testid="copilot-immersive-embedded-header-button"></div><div class="styles-module__itemDivider__nunbs hide-sm hide-md"></div><button data-component="ActionMenu.Button" type="button" aria-haspopup="true" aria-expanded="false" tabindex="0" class="prc-Button-ButtonBase-9n-Xk GlobalCreateMenu-module__actionMenuButton__Hj_iB GlobalCreateMenu-module__responsiveCreateMenu__zTmSP hide-sm" data-loading="false" data-size="medium" data-variant="invisible" aria-labelledby="global-create-menu-tooltip-_R_6f9_" id="_R_mf9_" style="anchor-name: --anchored-overlay-anchor-_R_bmf9H1_;"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="leadingVisual" class="prc-Button-Visual-YNt2F prc-Button-LeadingVisual-UySKu prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-plus" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M7.75 2a.75.75 0 0 1 .75.75V7h4.25a.75.75 0 0 1 0 1.5H8.5v4.25a.75.75 0 0 1-1.5 0V8.5H2.75a.75.75 0 0 1 0-1.5H7V2.75A.75.75 0 0 1 7.75 2Z"></path></svg></span></span><span data-component="trailingAction" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-triangle-down" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg></span></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" id="global-create-menu-tooltip-_R_6f9_" popover="auto">Create new...</span><div data-component="Stack" class="hide-sm hide-md prc-Stack-Stack-UQ9k6" data-gap="condensed" data-direction="horizontal" data-align="center" data-wrap="nowrap" data-justify="start" data-padding="none"><a data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_2of9_" href="https://github.com/issues" data-discover="true"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-issue-opened" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path><path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Z"></path></svg></a><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" id="_R_2of9_" popover="auto">All issues</span><a data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_38f9_" href="https://github.com/pulls" data-discover="true"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-git-pull-request" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M1.5 3.25a2.25 2.25 0 1 1 3 2.122v5.256a2.251 2.251 0 1 1-1.5 0V5.372A2.25 2.25 0 0 1 1.5 3.25Zm5.677-.177L9.573.677A.25.25 0 0 1 10 .854V2.5h1A2.5 2.5 0 0 1 13.5 5v5.628a2.251 2.251 0 1 1-1.5 0V5a1 1 0 0 0-1-1h-1v1.646a.25.25 0 0 1-.427.177L7.177 3.427a.25.25 0 0 1 0-.354ZM3.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm0 9.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm8.25.75a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Z"></path></svg></a><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" id="_R_38f9_" popover="auto">All pull requests</span><a data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_3of9_" href="https://github.com/repos" data-discover="true"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-repo" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path></svg></a><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" id="_R_3of9_" popover="auto">All repositories</span><div class="d-none"></div></div></div><a data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk styles-module__appHeaderButton__axedQ prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_2n9_" href="https://github.com/notifications" data-discover="true"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-inbox" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M2.8 2.06A1.75 1.75 0 0 1 4.41 1h7.18c.7 0 1.333.417 1.61 1.06l2.74 6.395c.04.093.06.194.06.295v4.5A1.75 1.75 0 0 1 14.25 15H1.75A1.75 1.75 0 0 1 0 13.25v-4.5c0-.101.02-.202.06-.295Zm1.61.44a.25.25 0 0 0-.23.152L1.887 8H4.75a.75.75 0 0 1 .6.3L6.625 10h2.75l1.275-1.7a.75.75 0 0 1 .6-.3h2.863L11.82 2.652a.25.25 0 0 0-.23-.152Zm10.09 7h-2.875l-1.275 1.7a.75.75 0 0 1-.6.3h-3.5a.75.75 0 0 1-.6-.3L4.375 9.5H1.5v3.75c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25Z"></path></svg></a><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" popover="auto"><span id="_R_2n9_">You have no unread notifications<span class="prc-src-InternalVisuallyHidden-2YaI6">(<!-- -->g then n<!-- -->)</span></span><span class="prc-TooltipV2-KeybindingHintContainer-Ymj-3 prc-TooltipV2-HasTextBefore-fdOXj" aria-hidden="true" data-component="Tooltip.KeybindingHintContainer"><kbd class="prc-KeybindingHint-KeybindingHint-qpYIs prc-Text-Text-9mHv3" data-component="KeybindingHint" data-testid="keybinding-hint"><span class="prc-components-Chord-DdhWN prc-components-ChordOnEmphasis-O-4BS prc-components-ChordSmall-c-P-x prc-Text-Text-9mHv3" data-component="Text" data-kbd-chord="true"> <span class="prc-src-InternalVisuallyHidden-2YaI6">g</span><span aria-hidden="true">G</span></span><span class="prc-src-InternalVisuallyHidden-2YaI6">then</span> <span class="prc-components-Chord-DdhWN prc-components-ChordOnEmphasis-O-4BS prc-components-ChordSmall-c-P-x prc-Text-Text-9mHv3" data-component="Text" data-kbd-chord="true"> <span class="prc-src-InternalVisuallyHidden-2YaI6">n</span><span aria-hidden="true">N</span></span></kbd></span></span><div class="d-none"></div><div class="GlobalNavUserMenu-module__container__NaVIt"><button data-component="IconButton" type="button" aria-haspopup="menu" data-login="joshamanangbao-design" class="prc-Button-ButtonBase-9n-Xk GlobalNavUserMenu-module__anchor__Dcej6 prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_av9_"><img data-component="Avatar" class="prc-Avatar-Avatar-0xaUi" alt="User avatar" width="32" height="32" style="--avatarSize-regular:32px" src="./README_files/341214825" data-testid="github-avatar"></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" aria-hidden="true" id="_R_av9_" popover="auto">Open user navigation menu</span></div></div></div><h2 class="prc-src-InternalVisuallyHidden-2YaI6">Repository navigation</h2><nav class="prc-components-UnderlineWrapper-eT-Yj prc-UnderlineNav-UnderlineWrapper-GWONT LocalNavigation-module__LocalNavigation__b0Xc0" aria-label="Repository" data-variant="inset" data-overflow-mode="wrap" data-hide-icons-breakpoint="medium"><ul class="prc-UnderlineNav-ItemsList-oj8gN prc-components-UnderlineItemList-xKlKC" role="list"><li role="presentation" aria-hidden="true" class="prc-UnderlineNav-WrapSpacer--aLgz"></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a aria-current="page" data-tab-item="code" data-react-nav="code-view" data-react-nav-anchor="code-view-repo-link" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-code" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m11.28 3.22 4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L13.94 8l-3.72-3.72a.749.749 0 0 1 .326-1.275.749.749 0 0 1 .734.215Zm-6.56 0a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042L2.06 8l3.72 3.72a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L.47 8.53a.75.75 0 0 1 0-1.06Z"></path></svg></span><span data-component="text" data-content="Code">Code</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="issues" data-react-nav="repo" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/issues" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-issue-opened" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path><path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Z"></path></svg></span><span data-component="text" data-content="Issues">Issues</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="pull-requests" data-react-nav="repo" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/pulls" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-git-pull-request" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M1.5 3.25a2.25 2.25 0 1 1 3 2.122v5.256a2.251 2.251 0 1 1-1.5 0V5.372A2.25 2.25 0 0 1 1.5 3.25Zm5.677-.177L9.573.677A.25.25 0 0 1 10 .854V2.5h1A2.5 2.5 0 0 1 13.5 5v5.628a2.251 2.251 0 1 1-1.5 0V5a1 1 0 0 0-1-1h-1v1.646a.25.25 0 0 1-.427.177L7.177 3.427a.25.25 0 0 1 0-.354ZM3.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm0 9.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm8.25.75a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Z"></path></svg></span><span data-component="text" data-content="Pull requests">Pull requests</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="actions" data-react-nav="actions-workflows" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/actions" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-play" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Zm4.879-2.773 4.264 2.559a.25.25 0 0 1 0 .428l-4.264 2.559A.25.25 0 0 1 6 10.559V5.442a.25.25 0 0 1 .379-.215Z"></path></svg></span><span data-component="text" data-content="Actions">Actions</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="projects" data-react-nav="repo" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/projects" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-table" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25ZM6.5 6.5v8h7.75a.25.25 0 0 0 .25-.25V6.5Zm8-1.5V1.75a.25.25 0 0 0-.25-.25H6.5V5Zm-13 1.5v7.75c0 .138.112.25.25.25H5v-8ZM5 5V1.5H1.75a.25.25 0 0 0-.25.25V5Z"></path></svg></span><span data-component="text" data-content="Projects">Projects</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="wiki" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/wiki" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-book" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M0 1.75A.75.75 0 0 1 .75 1h4.253c1.227 0 2.317.59 3 1.501A3.743 3.743 0 0 1 11.006 1h4.245a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-4.507a2.25 2.25 0 0 0-1.591.659l-.622.621a.75.75 0 0 1-1.06 0l-.622-.621A2.25 2.25 0 0 0 5.258 13H.75a.75.75 0 0 1-.75-.75Zm7.251 10.324.004-5.073-.002-2.253A2.25 2.25 0 0 0 5.003 2.5H1.5v9h3.757a3.75 3.75 0 0 1 1.994.574ZM8.755 4.75l-.004 7.322a3.752 3.752 0 0 1 1.992-.572H14.5v-9h-3.495a2.25 2.25 0 0 0-2.25 2.25Z"></path></svg></span><span data-component="text" data-content="Wiki">Wiki</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="security-and-quality" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/security" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-shield" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M7.467.133a1.748 1.748 0 0 1 1.066 0l5.25 1.68A1.75 1.75 0 0 1 15 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.697 1.697 0 0 1-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 0 1 1.217-1.667Zm.61 1.429a.25.25 0 0 0-.153 0l-5.25 1.68a.25.25 0 0 0-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.196.196 0 0 0 .154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.251.251 0 0 0-.174-.237l-5.25-1.68ZM8.75 4.75v3a.75.75 0 0 1-1.5 0v-3a.75.75 0 0 1 1.5 0ZM9 10.5a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path></svg></span><span data-component="text" data-content="Security and quality">Security and quality</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="insights" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/pulse" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-graph" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M1.5 1.75V13.5h13.75a.75.75 0 0 1 0 1.5H.75a.75.75 0 0 1-.75-.75V1.75a.75.75 0 0 1 1.5 0Zm14.28 2.53-5.25 5.25a.75.75 0 0 1-1.06 0L7 7.06 4.28 9.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.25-3.25a.75.75 0 0 1 1.06 0L10 7.94l4.72-4.72a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path></svg></span><span data-component="text" data-content="Insights">Insights</span></a></li><li class="prc-UnderlineNav-UnderlineNavItem-syRjR"><a data-tab-item="settings" data-turbo-frame="repo-content-turbo-frame" class="prc-components-UnderlineItem-7fP-n" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/settings" data-discover="true"><span data-component="icon"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-gear" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M8 0a8.2 8.2 0 0 1 .701.031C9.444.095 9.99.645 10.16 1.29l.288 1.107c.018.066.079.158.212.224.231.114.454.243.668.386.123.082.233.09.299.071l1.103-.303c.644-.176 1.392.021 1.82.63.27.385.506.792.704 1.218.315.675.111 1.422-.364 1.891l-.814.806c-.049.048-.098.147-.088.294.016.257.016.515 0 .772-.01.147.038.246.088.294l.814.806c.475.469.679 1.216.364 1.891a7.977 7.977 0 0 1-.704 1.217c-.428.61-1.176.807-1.82.63l-1.102-.302c-.067-.019-.177-.011-.3.071a5.909 5.909 0 0 1-.668.386c-.133.066-.194.158-.211.224l-.29 1.106c-.168.646-.715 1.196-1.458 1.26a8.006 8.006 0 0 1-1.402 0c-.743-.064-1.289-.614-1.458-1.26l-.289-1.106c-.018-.066-.079-.158-.212-.224a5.738 5.738 0 0 1-.668-.386c-.123-.082-.233-.09-.299-.071l-1.103.303c-.644.176-1.392-.021-1.82-.63a8.12 8.12 0 0 1-.704-1.218c-.315-.675-.111-1.422.363-1.891l.815-.806c.05-.048.098-.147.088-.294a6.214 6.214 0 0 1 0-.772c.01-.147-.038-.246-.088-.294l-.815-.806C.635 6.045.431 5.298.746 4.623a7.92 7.92 0 0 1 .704-1.217c.428-.61 1.176-.807 1.82-.63l1.102.302c.067.019.177.011.3-.071.214-.143.437-.272.668-.386.133-.066.194-.158.211-.224l.29-1.106C6.009.645 6.556.095 7.299.03 7.53.01 7.764 0 8 0Zm-.571 1.525c-.036.003-.108.036-.137.146l-.289 1.105c-.147.561-.549.967-.998 1.189-.173.086-.34.183-.5.29-.417.278-.97.423-1.529.27l-1.103-.303c-.109-.03-.175.016-.195.045-.22.312-.412.644-.573.99-.014.031-.021.11.059.19l.815.806c.411.406.562.957.53 1.456a4.709 4.709 0 0 0 0 .582c.032.499-.119 1.05-.53 1.456l-.815.806c-.081.08-.073.159-.059.19.162.346.353.677.573.989.02.03.085.076.195.046l1.102-.303c.56-.153 1.113-.008 1.53.27.161.107.328.204.501.29.447.222.85.629.997 1.189l.289 1.105c.029.109.101.143.137.146a6.6 6.6 0 0 0 1.142 0c.036-.003.108-.036.137-.146l.289-1.105c.147-.561.549-.967.998-1.189.173-.086.34-.183.5-.29.417-.278.97-.423 1.529-.27l1.103.303c.109.029.175-.016.195-.045.22-.313.411-.644.573-.99.014-.031.021-.11-.059-.19l-.815-.806c-.411-.406-.562-.957-.53-1.456a4.709 4.709 0 0 0 0-.582c-.032-.499.119-1.05.53-1.456l.815-.806c.081-.08.073-.159.059-.19a6.464 6.464 0 0 0-.573-.989c-.02-.03-.085-.076-.195-.046l-1.102.303c-.56.153-1.113.008-1.53-.27a4.44 4.44 0 0 0-.501-.29c-.447-.222-.85-.629-.997-1.189l-.289-1.105c-.029-.11-.101-.143-.137-.146a6.6 6.6 0 0 0-1.142 0ZM11 8a3 3 0 1 1-6 0 3 3 0 0 1 6 0ZM9.5 8a1.5 1.5 0 1 0-3.001.001A1.5 1.5 0 0 0 9.5 8Z"></path></svg></span><span data-component="text" data-content="Settings">Settings</span></a></li></ul><div class="prc-UnderlineNav-MoreButtonContainer-Dnrq6"><div class="prc-UnderlineNav-MoreButtonDivider-dN0a-"></div><button data-component="overflow-menu-button" type="button" aria-haspopup="true" aria-expanded="false" tabindex="0" class="prc-Button-ButtonBase-9n-Xk prc-UnderlineNav-MoreButton-Y8soj" data-loading="false" data-size="medium" data-variant="invisible" id="_R_1afp_" style="anchor-name: --anchored-overlay-anchor-_R_7afpH1_;"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="text" class="prc-Button-Label-FWkx3"><span>More<span class="prc-src-InternalVisuallyHidden-2YaI6"> items</span></span></span></span><span data-component="trailingAction" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-triangle-down" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg></span></button></div></nav><div class="d-none"></div></header></div>
</react-partial>




      <div hidden="hidden" data-view-component="true" class="js-stale-session-flash stale-session-flash flash flash-warn flash-full">
  
        <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
        <span class="js-stale-session-flash-signed-in" hidden="">You signed in with another tab or window. <a class="Link--inTextBlock" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload">Reload</a> to refresh your session.</span>
        <span class="js-stale-session-flash-signed-out" hidden="">You signed out in another tab or window. <a class="Link--inTextBlock" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload">Reload</a> to refresh your session.</span>
        <span class="js-stale-session-flash-switched" hidden="">You switched accounts on another tab or window. <a class="Link--inTextBlock" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload">Reload</a> to refresh your session.</span>

    <button id="icon-button-87f9c440-b7bc-4907-8f67-f9ca3716ce66" aria-labelledby="tooltip-1f4c9e08-0727-42a6-af3c-c7909a5c19cc" type="button" data-view-component="true" class="Button Button--iconOnly Button--invisible Button--medium flash-close js-flash-close">  <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x Button-visual">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
</button><tool-tip id="tooltip-1f4c9e08-0727-42a6-af3c-c7909a5c19cc" for="icon-button-87f9c440-b7bc-4907-8f67-f9ca3716ce66" popover="manual" data-direction="s" data-type="label" data-view-component="true" class="sr-only position-absolute" aria-hidden="true" role="tooltip"><template shadowrootmode="open"><style>
      :host {
        --tooltip-top: var(--tool-tip-position-top, 0);
        --tooltip-left: var(--tool-tip-position-left, 0);
        padding: var(--overlay-paddingBlock-condensed) var(--overlay-padding-condensed) !important;
        font: var(--text-body-shorthand-small);
        color: var(--tooltip-fgColor, var(--fgColor-onEmphasis)) !important;
        text-align: center;
        text-decoration: none;
        text-shadow: none;
        text-transform: none;
        letter-spacing: normal;
        word-wrap: break-word;
        white-space: pre;
        background: var(--tooltip-bgColor, var(--bgColor-emphasis)) !important;
        border-radius: var(--borderRadius-medium);
        border: 0 !important;
        opacity: 0;
        max-width: min(var(--overlay-width-small), 100vw);
        word-wrap: break-word;
        white-space: normal;
        width: max-content !important;
        inset: var(--tooltip-top) auto auto var(--tooltip-left) !important;
        overflow: visible !important;
        text-wrap: balance;
      }

      :host(:is(.tooltip-n, .tooltip-nw, .tooltip-ne)) {
        --tooltip-top: calc(var(--tool-tip-position-top, 0) - var(--overlay-offset, 0.25rem));
        --tooltip-left: var(--tool-tip-position-left);
      }

      :host(:is(.tooltip-s, .tooltip-sw, .tooltip-se)) {
        --tooltip-top: calc(var(--tool-tip-position-top, 0) + var(--overlay-offset, 0.25rem));
        --tooltip-left: var(--tool-tip-position-left);
      }

      :host(.tooltip-w) {
        --tooltip-top: var(--tool-tip-position-top);
        --tooltip-left: calc(var(--tool-tip-position-left, 0) - var(--overlay-offset, 0.25rem));
      }

      :host(.tooltip-e) {
        --tooltip-top: var(--tool-tip-position-top);
        --tooltip-left: calc(var(--tool-tip-position-left, 0) + var(--overlay-offset, 0.25rem));
      }

      :host:after{
        position: absolute;
        display: block;
        right: 0;
        left: 0;
        height: var(--overlay-offset, 0.25rem);
        content: "";
      }

      :host(.tooltip-s):after,
      :host(.tooltip-se):after,
      :host(.tooltip-sw):after {
        bottom: 100%
      }

      :host(.tooltip-n):after,
      :host(.tooltip-ne):after,
      :host(.tooltip-nw):after {
        top: 100%;
      }

      @keyframes tooltip-appear {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }

      :host(:popover-open),
      :host(:popover-open):before {
        animation-name: tooltip-appear;
        animation-duration: .1s;
        animation-fill-mode: forwards;
        animation-timing-function: ease-in;
      }

      :host(.\:popover-open) {
        animation-name: tooltip-appear;
        animation-duration: .1s;
        animation-fill-mode: forwards;
        animation-timing-function: ease-in;
      }

      @media (forced-colors: active) {
        :host {
          outline: solid 1px transparent;
        }

        :host:before {
          display: none;
        }
      }
    </style><slot></slot></template>Dismiss alert</tool-tip>


  
</div>
        
          
          <include-fragment src="/in-product-messaging/code-scanning-ai-findings-preview-banner?page_path=%2Fjoshamanangbao-design%2FDistanceCalculatorProgram" data-nonce="v2:9e10e5d5-c294-0699-45fd-63fdda7ed45b" data-view-component="true" class="is-error"><template shadowrootmode="open"><style>:host {display: block;}</style><slot></slot></template>
  
  <div data-show-on-forbidden-error="" hidden="">
    <div class="Box">
  <div class="blankslate-container">
    <div data-view-component="true" class="blankslate blankslate-spacious color-bg-default rounded-2">
      

      <h3 data-view-component="true" class="blankslate-heading">        Uh oh!
</h3>
      <p data-view-component="true" class="blankslate-description">        </p><p class="color-fg-muted my-2 mb-2 ws-normal">There was an error while loading. <a class="Link--inTextBlock" data-turbo="false" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload" aria-label="Please reload this page">Please reload this page</a>.</p>
<p></p>

</div>  </div>
</div>  </div>
</include-fragment>

          
    </div>

  <div id="start-of-content" class="show-on-focus"></div>








    <div id="js-flash-container" class="flash-container" data-turbo-replace="">






  <template class="js-flash-template"></template>
</div>


    
  <notification-shelf-watcher data-base-url="https://github.com/notifications/beta/shelf" data-channel="eyJjIjoibm90aWZpY2F0aW9uLWNoYW5nZWQ6MzQxMjE0ODI1IiwidCI6MTc5MTc2OTAwMX0=--9ba0cce63039293c3a6e04a72a7cace77853c6eb9060dc5a4976e83f9d47c805" data-view-component="true" class="js-socket-channel" data-refresh-delay="500" data-catalyst="" data-throttle-delay="5000"></notification-shelf-watcher>
  <div hidden="" data-initial="" data-target="notification-shelf-watcher.placeholder"></div>






  <div class="application-main " data-commit-hovercards-enabled="" data-discussion-hovercards-enabled="" data-issue-and-pr-hovercards-enabled="" data-project-hovercards-enabled="">
        <div itemscope="" itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main id="js-repo-pjax-container">
      
  
    








  
    

    <div id="repository-container-header" data-turbo-replace="" hidden=""></div>



<turbo-frame id="repo-content-turbo-frame" target="_top" data-turbo-action="advance" class="" src="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload" complete="">
    
    
<div class="clearfix container-xl tmp-px-3 tmp-px-md-4 tmp-px-lg-5 tmp-mt-4">
  <h1 class="sr-only">Uploading files to DistanceCalculatorProgram</h1>

  <div class="breadcrumb repo-upload-breadcrumb">
    <h2 class="sr-only">Breadcrumbs</h2>
    <span class="css-truncate-target">
      <span class="js-repo-root text-bold"><span class="js-path-segment d-inline-block wb-break-all"><a href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload"><span>DistanceCalculatorProgram</span></a></span></span><span class="separator">/</span>
    </span>
  </div>

    <h2 class="sr-only">Upload files</h2>
    <div class="js-upload-manifest-file-container">
      <!-- '"` --><!-- </textarea></xmp> --><form class="d-none js-upload-manifest-form" data-turbo="false" action="https://github.com/upload/manifests" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="57h-XIYy7it2r3Cousj19f2BAzAQBvdSleDSXS4Aj1Y1e-2BU1ilB6CVwZx8cqRpNiq3hpEbiKhotk20BcHMfA">
        <input type="hidden" name="repository_id" value="1414928862">
        <input type="hidden" name="directory_binary" value="">
</form>
      <!-- '"` --><!-- </textarea></xmp> --><form data-turbo="false" action="https://github.com/upload/upload-manifest-files" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="NS16vP84kFWk3iE0F59ljVuUr6qlequgw6CB1J7ybpJcQ8Mp64EtHGZubqmwSpvEjlripJq87WZGPUYp_M-rsQ">
        <file-attachment class="d-block tmp-mb-3 Box blankslate blankslate-spacious js-upload-manifest-file repo-file-upload-target is-file-list is-default" input="upload-manifest-files-input" data-upload-repository-id="1414928862" data-directory-upload-max-files="100" directory="true" data-upload-policy-url="/upload/policies/upload-manifest-files"><input type="hidden" value="ME2Y0kvaoU9l3-37gpOf0WgoZxckJ-HG1fz2ooqUt7VfW4yks3Js4z6sRIrtL3b_qQgEQztx2hYHbIiB5EhYyw" data-csrf="true" class="js-data-upload-policy-url-csrf">

          <div class="repo-file-upload-outline"></div>
          <svg height="32" aria-hidden="true" data-component="Octicon" viewBox="0 0 24 24" version="1.1" width="32" data-view-component="true" class="octicon octicon-file mb-2 tmp-mb-2 color-fg-muted">
    <path d="M3 3a2 2 0 0 1 2-2h9.982a2 2 0 0 1 1.414.586l4.018 4.018A2 2 0 0 1 21 7.018V21a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm2-.5a.5.5 0 0 0-.5.5v18a.5.5 0 0 0 .5.5h14a.5.5 0 0 0 .5-.5V8.5h-4a2 2 0 0 1-2-2v-4Zm10 0v4a.5.5 0 0 0 .5.5h4a.5.5 0 0 0-.146-.336l-4.018-4.018A.5.5 0 0 0 15 2.5Z"></path>
</svg>
          <span class="repo-file-upload-text initial-text h2">Drag files here to add them to your repository</span>
          <span class="repo-file-upload-text alternate-text h2">Drag additional files here to add them to your repository</span>
          <span class="repo-file-upload-drop-text h2">Drop to upload your files</span>

          <p class="repo-file-upload-choose">
            Or
            <input type="file" multiple="" class="manual-file-chooser" id="upload-manifest-files-input" aria-label="Choose your files">
            <span class="manual-file-chooser-text btn-link" aria-hidden="true" tabindex="-1">choose your files</span>
          </p>

          <div class="repo-file-upload-errors">
            <span class="error too-big">
              Yowza, that’s a big file. Try again with a file smaller than 25MB.
            </span>
            <span class="error too-many">
              Yowza, that’s a lot of files. Try uploading fewer than 100 at a time.
            </span>
            <span class="error empty">
              This file is empty.
            </span>
            <span class="error hidden-file">
              This file is hidden.
            </span>
            <span class="error failed-request">
              Something went really wrong, and we can’t process that file.
            </span>
          </div>
</file-attachment></form>
      <div class="tmp-mb-3 js-upload-progress" hidden="">
        <div class="mb-2 f4 js-upload-meter-text">
          <div class="d-flex flex-items-center mb-1">
            <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-file mr-2 tmp-mr-2">
    <path d="M2 1.75C2 .784 2.784 0 3.75 0h6.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v9.586A1.75 1.75 0 0 1 13.25 16h-9.5A1.75 1.75 0 0 1 2 14.25Zm1.75-.25a.25.25 0 0 0-.25.25v12.5c0 .138.112.25.25.25h9.5a.25.25 0 0 0 .25-.25V6h-2.75A1.75 1.75 0 0 1 9 4.25V1.5Zm6.75.062V4.25c0 .138.112.25.25.25h2.688l-.011-.013-2.914-2.914-.013-.011Z"></path>
</svg>
            <div class="js-upload-meter-filename"></div>
          </div>
          <div class="f6">
            Uploading <span class="js-upload-meter-range-start">1</span> of <span class="js-upload-meter-range-end">1</span> files
          </div>
        </div>
        <div class="Progress Progress--large">
          <span class="color-bg-success-emphasis js-upload-meter" style="width: 100%;"></span>
        </div>
      </div>
    </div>

    <div class="js-manifest-commit-file-template" hidden="">
      <div class="js-manifest-file-entry Box-row d-flex">
        <div class="mr-2 flex-shrink-0">
          <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-file">
    <path d="M2 1.75C2 .784 2.784 0 3.75 0h6.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v9.586A1.75 1.75 0 0 1 13.25 16h-9.5A1.75 1.75 0 0 1 2 14.25Zm1.75-.25a.25.25 0 0 0-.25.25v12.5c0 .138.112.25.25.25h9.5a.25.25 0 0 0 .25-.25V6h-2.75A1.75 1.75 0 0 1 9 4.25V1.5Zm6.75.062V4.25c0 .138.112.25.25.25h2.688l-.011-.013-2.914-2.914-.013-.011Z"></path>
</svg>
        </div>
        <div class="js-filename flex-auto min-width-0 css-truncate css-truncate-target width-fit tmp-mr-3"></div>
        <!-- '"` --><!-- </textarea></xmp> --><form class="js-remove-manifest-file-form" data-turbo="false" action="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload" accept-charset="UTF-8" method="post"><input type="hidden" name="_method" value="delete" autocomplete="off"><input type="hidden" name="authenticity_token" value="2nWlLqOgoasABzZ8AWopbfwpUeaexMtmItFupuK_H1GPZ0k1BAxHtJvign0bCnyuPVP57b7XLTAzzlqaIgElUw">
          <input type="hidden" name="file_id" value="">
            <button aria-label="Remove this file" type="submit" data-view-component="true" class="Link--primary btn-link">    <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
</button></form>      </div>
    </div>

    <div class="Box tmp-mb-3 js-manifest-file-list">
      <div class="js-manifest-file-list-root"><div class="js-manifest-file-entry Box-row d-flex">
        <div class="mr-2 flex-shrink-0">
          <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-file">
    <path d="M2 1.75C2 .784 2.784 0 3.75 0h6.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v9.586A1.75 1.75 0 0 1 13.25 16h-9.5A1.75 1.75 0 0 1 2 14.25Zm1.75-.25a.25.25 0 0 0-.25.25v12.5c0 .138.112.25.25.25h9.5a.25.25 0 0 0 .25-.25V6h-2.75A1.75 1.75 0 0 1 9 4.25V1.5Zm6.75.062V4.25c0 .138.112.25.25.25h2.688l-.011-.013-2.914-2.914-.013-.011Z"></path>
</svg>
        </div>
        <div class="js-filename flex-auto min-width-0 css-truncate css-truncate-target width-fit tmp-mr-3">script (9).py</div>
        <!-- '"` --><!-- </textarea></xmp> --><form class="js-remove-manifest-file-form" data-turbo="false" action="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload" accept-charset="UTF-8" method="post"><input type="hidden" name="_method" value="delete" autocomplete="off"><input type="hidden" name="authenticity_token" value="2nWlLqOgoasABzZ8AWopbfwpUeaexMtmItFupuK_H1GPZ0k1BAxHtJvign0bCnyuPVP57b7XLTAzzlqaIgElUw">
          <input type="hidden" name="file_id" value="3767437867">
            <button aria-label="Remove script (9).py" type="submit" data-view-component="true" class="Link--primary btn-link">    <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
</button></form>      </div></div>
    </div>

    <!-- '"` --><!-- </textarea></xmp> --><form class="file-commit-form manifest-commit-form js-file-commit-form js-manifest-commit-form" data-turbo="false" action="https://github.com/joshamanangbao-design/DistanceCalculatorProgram/upload" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="cjKsVPQXEV2RgBRVTP5VdXVwzizPufpXKe7h1KcnTwKL8SwFPi4Qr78f3Z9WCCFB1CoRaQIiBS5S-X4IT6Pi8g">
      <img class="commit-form-avatar float-left rounded-2 avatar-user" src="./README_files/341214825(1)" width="48" height="48" alt="@joshamanangbao-design">

      <div class="commit-form position-relative tmp-p-3 mb-2 border rounded-2" data-hpc="true">
        <h3>Commit changes</h3>

        <div class="color-fg-severe js-too-long-error d-none">
          <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-light-bulb">
    <path d="M8 1.5c-2.363 0-4 1.69-4 3.75 0 .984.424 1.625.984 2.304l.214.253c.223.264.47.556.673.848.284.411.537.896.621 1.49a.75.75 0 0 1-1.484.211c-.04-.282-.163-.547-.37-.847a8.456 8.456 0 0 0-.542-.68c-.084-.1-.173-.205-.268-.32C3.201 7.75 2.5 6.766 2.5 5.25 2.5 2.31 4.863 0 8 0s5.5 2.31 5.5 5.25c0 1.516-.701 2.5-1.328 3.259-.095.115-.184.22-.268.319-.207.245-.383.453-.541.681-.208.3-.33.565-.37.847a.751.751 0 0 1-1.485-.212c.084-.593.337-1.078.621-1.489.203-.292.45-.584.673-.848.075-.088.147-.173.213-.253.561-.679.985-1.32.985-2.304 0-2.06-1.637-3.75-4-3.75ZM5.75 12h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5ZM6 15.25a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75Z"></path>
</svg>
          <strong>ProTip!</strong> Great commit summaries contain fewer than 50 characters. Place extra information in the extended description.
        </div>

        <label for="commit-summary-input" class="sr-only">
          Commit summary
        </label>
        <input id="commit-summary-input" type="text" class="form-control input-block input-contrast js-new-blob-commit-summary js-quick-submit" placeholder="Add files via upload" autocomplete="off" name="message">

        <label for="commit-description-textarea" class="sr-only">
          Optional extended description
        </label>
        <textarea id="commit-description-textarea" name="description" class="form-control input-block input-contrast comment-form-textarea js-quick-submit" placeholder="Add an optional extended description…"></textarea>

        

          <input type="hidden" name="commit-choice" value="direct">
        <input type="hidden" name="manifest_id" value="455852442">
      </div>

        <button data-edit-text="Commit changes" data-pull-text="Propose changes" type="submit" data-view-component="true" class="js-blob-submit btn-primary btn">    Commit changes
</button>
      <a class="btn btn-danger" href="https://github.com/joshamanangbao-design/DistanceCalculatorProgram">Cancel</a>
</form>
</div>

  </turbo-frame>


    </main>
  </div>

  </div>

          <footer class="footer f6 color-fg-muted color-border-subtle tmp-pt-7 tmp-pb-6 p-responsive" role="contentinfo">
  <h2 class="sr-only">Footer</h2>

  


  <div class="d-flex flex-justify-center flex-items-center flex-column-reverse flex-lg-row flex-wrap flex-lg-nowrap">
    <div class="d-flex flex-items-center flex-shrink-0 mx-2">
      <a aria-label="GitHub Homepage" class="footer-octicon mr-2" href="https://github.com/">
        <svg aria-hidden="true" data-component="Octicon" height="24" viewBox="0 0 24 24" version="1.1" width="24" data-view-component="true" class="octicon octicon-mark-github">
    <path d="M10.226 17.284c-2.965-.36-5.054-2.493-5.054-5.256 0-1.123.404-2.336 1.078-3.144-.292-.741-.247-2.314.09-2.965.898-.112 2.111.36 2.83 1.01.853-.269 1.752-.404 2.853-.404 1.1 0 1.999.135 2.807.382.696-.629 1.932-1.1 2.83-.988.315.606.36 2.179.067 2.942.72.854 1.101 2 1.101 3.167 0 2.763-2.089 4.852-5.098 5.234.763.494 1.28 1.572 1.28 2.807v2.336c0 .674.561 1.056 1.235.786 4.066-1.55 7.255-5.615 7.255-10.646C23.5 6.188 18.334 1 11.978 1 5.62 1 .5 6.188.5 12.545c0 4.986 3.167 9.12 7.435 10.669.606.225 1.19-.18 1.19-.786V20.63a2.9 2.9 0 0 1-1.078.224c-1.483 0-2.359-.808-2.987-2.313-.247-.607-.517-.966-1.034-1.033-.27-.023-.359-.135-.359-.27 0-.27.45-.471.898-.471.652 0 1.213.404 1.797 1.235.45.651.921.943 1.483.943.561 0 .92-.202 1.437-.719.382-.381.674-.718.944-.943"></path>
</svg>
</a>
      <span>
        © 2026 GitHub,&nbsp;Inc.
      </span>
    </div>

    <nav aria-label="Footer">
      <h3 class="sr-only" id="sr-footer-heading">Footer navigation</h3>

      <ul class="list-style-none d-flex flex-justify-center flex-wrap mb-2 mb-lg-0" aria-labelledby="sr-footer-heading">


          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to Terms&quot;,&quot;label&quot;:&quot;text:terms&quot;}" href="https://docs.github.com/site-policy/github-terms/github-terms-of-service" data-view-component="true" class="Link--secondary Link">Terms</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to privacy&quot;,&quot;label&quot;:&quot;text:privacy&quot;}" href="https://docs.github.com/site-policy/privacy-policies/github-privacy-statement" data-view-component="true" class="Link--secondary Link">Privacy</a>
          </li>


            <li class="mx-2">
              <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to security&quot;,&quot;label&quot;:&quot;text:security&quot;}" href="https://github.com/security" data-view-component="true" class="Link--secondary Link">Security</a>
            </li>

            <li class="mx-2">
              <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to status&quot;,&quot;label&quot;:&quot;text:status&quot;}" href="https://www.githubstatus.com/" data-view-component="true" class="Link--secondary Link">Status</a>
            </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to community&quot;,&quot;label&quot;:&quot;text:community&quot;}" href="https://github.community/" data-view-component="true" class="Link--secondary Link">Community</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to docs&quot;,&quot;label&quot;:&quot;text:docs&quot;}" href="https://docs.github.com/" data-view-component="true" class="Link--secondary Link">Docs</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to contact&quot;,&quot;label&quot;:&quot;text:contact&quot;}" href="https://support.github.com/?tags=dotcom-footer" data-view-component="true" class="Link--secondary Link">Contact</a>
          </li>

          
<li class="mx-2">
  <cookie-consent-link data-catalyst="">
    <button type="button" class="Link--secondary underline-on-hover border-0 p-0 color-bg-transparent" data-action="click:cookie-consent-link#showConsentManagement" data-analytics-event="{&quot;location&quot;:&quot;footer&quot;,&quot;action&quot;:&quot;cookies&quot;,&quot;context&quot;:&quot;subfooter&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;label&quot;:&quot;cookies_link_subfooter_footer&quot;}">
      Manage cookies
    </button>
  </cookie-consent-link>
</li>

  <li class="mx-2">
    <cookie-consent-link data-catalyst="">
      <button type="button" class="Link--secondary underline-on-hover border-0 p-0 color-bg-transparent text-left" data-action="click:cookie-consent-link#showConsentManagement" data-analytics-event="{&quot;location&quot;:&quot;footer&quot;,&quot;action&quot;:&quot;dont_share_info&quot;,&quot;context&quot;:&quot;subfooter&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;label&quot;:&quot;dont_share_info_link_subfooter_footer&quot;}">
        Do not share my personal information
      </button>
    </cookie-consent-link>
  </li>

      </ul>
    </nav>
  </div>
</footer>



    <ghcc-consent id="ghcc" class="position-fixed bottom-0 left-0" style="z-index: 999999" data-locale="en" data-initial-cookie-consent-allowed="" data-cookie-consent-required="false" data-catalyst=""></ghcc-consent>




  <div id="ajax-error-message" class="ajax-error-message flash flash-error" hidden="">
    <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" data-component="Octicon" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
    </button>
    You can’t perform that action at this time.
  </div>

    <template id="site-details-dialog"></template>

    <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box color-shadow-large" style="width:360px;"></div>
</div>

    <template id="snippet-clipboard-copy-button"></template>
<template id="snippet-clipboard-copy-button-unpositioned"></template>


    <style>
      .user-mention[href$="/joshamanangbao-design"] {
        color: var(--color-user-mention-fg);
        background-color: var(--bgColor-attention-muted, var(--color-attention-subtle));
        border-radius: 2px;
        margin-left: -2px;
        margin-right: -2px;
      }
      .user-mention[href$="/joshamanangbao-design"]:before,
      .user-mention[href$="/joshamanangbao-design"]:after {
        content: '';
        display: inline-block;
        width: 2px;
      }
    </style>


    </div>
    <div id="js-global-screen-reader-notice" class="sr-only mt-n1" aria-live="polite" aria-atomic="true"></div>
    <div id="js-global-screen-reader-notice-assertive" class="sr-only mt-n1" aria-live="assertive" aria-atomic="true"></div>
  


</body></html>