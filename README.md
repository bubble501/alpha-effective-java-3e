# Effective Java 3rd Edition


* [Introduction](README.md)
* [1 Prefix](1_prefix/README.md)
* [2 Creating and Destroying Objects](2_creating_and_destroying_objects/README.md)
   * [Item 1: Consider static factory methods instead of constructors](2_creating_and_destroying_objects/item_1_consider_static_factory_methods_instead_of_constructors.md)
   * [Item 2: Consider a builder when faced with many constructor parameters](2_creating_and_destroying_objects/item_2_consider_a_builder_when_faced_with_many_constructor_parameters.md)
   * [Item 3: Enforce the singleton property with a private constructor or an enum type  ](2_creating_and_destroying_objects/item_3_enforce_the_singleton_property_with_a_private_constructor_or_an_enum_type_.md)
   * [Item 4: Enforce noninstantiability with a private constructor](2_creating_and_destroying_objects/item_4_enforce_noninstantiability_with_a_private_constructor.md)
   * [Item 5: Perfer dependecy injection to hardwiring resources](2_creating_and_destroying_objects/item_5_perfer_dependecy_injection_to_hardwiring_resources.md)
   * [Item 6: Avoid creating unnecessary objects](2_creating_and_destroying_objects/item_6_avoid_creating_unnecessary_objects.md)
   * [Item 7: Eliminate obsolete object references](2_creating_and_destroying_objects/item_7_eliminate_obsolete_object_references.md)
   * [Item 8: Avoid finalizers and cleaners](2_creating_and_destroying_objects/item_8_avoid_finalizers_and_cleaners.md)
   * [Item 9: Prefer try-with-resources to try-finally](2_creating_and_destroying_objects/item_9_prefer_try-with-resources_to_try-finally.md)
* [3 Methods Common to All Objects](3_methods_common_to_all_objects/README.md)
   * [Item 10: Obey the general contract when overriding equals](3_methods_common_to_all_objects/item_10_obey_the_general_contract_when_overriding_equals.md)
   * [Item 11: Always override hashCode when you override equals](3_methods_common_to_all_objects/item_11_always_override_hashcode_when_you_override_equals.md)
   * [Item 12: Always override toString](3_methods_common_to_all_objects/item_12_always_override_tostring.md)
   * [Item 13: Override clone judiciously](3_methods_common_to_all_objects/item_13_override_clone_judiciously.md)
   * [Item 14: Consider implementing Comparable](3_methods_common_to_all_objects/item_14_consider_implementing_comparable.md)
* [4 Classes and Interfaces](4_classes_and_interfaces/README.md)
   * [Item 15: Minimize the accessibility of classes and members](4_classes_and_interfaces/item_15_minimize_the_accessibility_of_classes_and_members.md)
   * [Item 16: In public classes, use accessor methods, not public fields](4_classes_and_interfaces/item_16_in_public_classes,_use_accessor_methods,_not_public_fields.md)
   * [Item 17: Minimize mutability](4_classes_and_interfaces/item_17_minimize_mutability.md)
   * [Item 18: Favor composition over inheritance  ](4_classes_and_interfaces/item_18_favor_composition_over_inheritance_.md)
   * [Item 19: Design and document for inheritance or else prohibit  it  ](4_classes_and_interfaces/item_19_design_and_document_for_inheritance_or_else_prohibit__it_.md)
   * [Item 20: Prefer interfaces to abstract classes  ](4_classes_and_interfaces/item_20_prefer_interfaces_to_abstract_classes_.md)
   * [Item 21: Design interfaces for posterity](4_classes_and_interfaces/item_21_design_interfaces_for_posterity.md)
   * [Item 22: Use interfaces only to define types  ](4_classes_and_interfaces/item_22_use_interfaces_only_to_define_types_.md)
   * [Item 23: Prefer class hierarchies to tagged classes  ](4_classes_and_interfaces/item_23_prefer_class_hierarchies_to_tagged_classes_.md)
   * [Item 24: Favor static member classes over nonstatic](4_classes_and_interfaces/item_24_favor_static_member_classes_over_nonstatic.md)
   * [Item 25: Limit source files to a single top-level class](4_classes_and_interfaces/item_25_limit_source_files_to_a_single_top-level_class.md)
* [5 Generics](5_generics/README.md)
   * [Item 26: Don't use raw types](5_generics/item_26_dont_use_raw_types.md)
   * [Item 27: Eliminate unchecked warnings](5_generics/item_27_eliminate_unchecked_warnings.md)
   * [Item 28: Prefer lists to arrays](5_generics/item_28_prefer_lists_to_arrays.md)
   * [Item 29: Favor generic types](5_generics/item_29_favor_generic_types.md)
   * [Item 30: Favor generic methods](5_generics/item_30_favor_generic_methods.md)
   * [Item 31: Use bounded wildcards to increase API flexibility](5_generics/item_31_use_bounded_wildcards_to_increase_api_flexibility.md)
   * [Item 32: Combine generics and varargs judiciously](5_generics/item_32_combine_generics_and_varargs_judiciously.md)
   * [Item 33: Consider typesafe heterogeneous containers](5_generics/item_33_consider_typesafe_heterogeneous_containers.md)
* [6 Enums and Annotations](6_enums_and_annotations/README.md)
   * [Item 34: Use enums instead of int constants](6_enums_and_annotations/item_34_use_enums_instead_of_int_constants.md)
   * [Item 35: Use instance fields instead of ordinals](6_enums_and_annotations/item_35_use_instance_fields_instead_of_ordinals.md)
   * [Item 36: Use EnumSet instead of bit fields](6_enums_and_annotations/item_36_use_enumset_instead_of_bit_fields.md)
   * [Item 37: Use EnumMap instead of ordinal indexing](6_enums_and_annotations/item_37_use_enummap_instead_of_ordinal_indexing.md)
   * [Item 38: Emulate extensible enums with interfaces](6_enums_and_annotations/item_38_emulate_extensible_enums_with_interfaces.md)
   * [Item 39: Prefer annotations to naming patterns](6_enums_and_annotations/item_39_prefer_annotations_to_naming_patterns.md)
   * [Item 40: Consistently use the Override annotation](6_enums_and_annotations/item_40_consistently_use_the_override_annotation.md)
   * [Item 41: Use marker interfaces to define types](6_enums_and_annotations/item_41_use_marker_interfaces_to_define_types.md)
* [7 Lambdas and Streams](7_lambdas_and_streams/README.md)
   * [Item 42: Prefer lambdas to anonymous classes](7_lambdas_and_streams/item_42_prefer_lambdas_to_anonymous_classes.md)
   * [Item 43: Prefer method references to lambdas](7_lambdas_and_streams/item_43_prefer_method_references_to_lambdas.md)
   * [Item 44: Favor the use of standard functional interfaces](7_lambdas_and_streams/item_44_favor_the_use_of_standard_functional_interfaces.md)
   * [Item 45: Use streams judiciously](7_lambdas_and_streams/item_45_use_streams_judiciously.md)
   * [Item 46: Prefer side-effect-free functions in streams](7_lambdas_and_streams/item_46_prefer_side-effect-free_functions_in_streams.md)
   * [Item 47: Prefer Collection to Stream as a return type](7_lambdas_and_streams/item_47_prefer_collection_to_stream_as_a_return_type.md)
   * [Item 48: Use caution when making streams parallel](7_lambdas_and_streams/item_48_use_caution_when_making_streams_parallel.md)
* [8 Methods](8_methods/README.md)
   * [Item 49: Check parameters for validity](8_methods/item_49_check_parameters_for_validity.md)
   * [Item 50: Make defensive copies when needed](8_methods/item_50_make_defensive_copies_when_needed.md)
   * [Item 51: Design method signatures carefully](8_methods/item_51_design_method_signatures_carefully.md)
   * [Item 52: Use overloading judiciously](8_methods/item_52_use_overloading_judiciously.md)
   * [Item 53: Use varargs judiciously](8_methods/item_53_use_varargs_judiciously.md)
   * [Item 54: Return empty collections or arrays, not nulls](8_methods/item_54_return_empty_collections_or_arrays,_not_nulls.md)
   * [Item 55: Return optionals judiciouslly](8_methods/item_55_return_optionals_judiciouslly.md)
   * [Item 56: Write doc comments for all exposed API elements](8_methods/item_56_write_doc_comments_for_all_exposed_api_elements.md)
* [9 General Programming](9_general_programming/README.md)
   * [Item 57: Minimize the scope of local variables](9_general_programming/item_57_minimize_the_scope_of_local_variables.md)
   * [Item 58: Prefer for-each loops to traditional for loops](9_general_programming/item_58_prefer_for-each_loops_to_traditional_for_loops.md)
   * [Item 59: Know and use the libraries](9_general_programming/item_59_know_and_use_the_libraries.md)
   * [Item 60: Avoid float and double if exact answsers are required](9_general_programming/item_60_avoid_float_and_double_if_exact_answsers_are_required.md)
   * [Item 61: Prefer primitive types to boxed primitives](9_general_programming/item_61_prefer_primitive_types_to_boxed_primitives.md)
   * [Item 62: Avoid strings where other types are more appropriate](9_general_programming/item_62_avoid_strings_where_other_types_are_more_appropriate.md)
   * [Item 63: Beware the performance of string concatenation](9_general_programming/item_63_beware_the_performance_of_string_concatenation.md)
   * [Item 64: Refer to objects by their interfaces](9_general_programming/item_64_refer_to_objects_by_their_interfaces.md)
   * [Item 65: Prefer interfaces to reflection](9_general_programming/item_65_prefer_interfaces_to_reflection.md)
   * [Item 66: Use native methods judiciously](9_general_programming/item_66_use_native_methods_judiciously.md)
   * [Item 67: Optimize judiciously](9_general_programming/item_67_optimize_judiciously.md)
   * [Item 68: Adhere to generally accepted naming conventions](9_general_programming/item_68_adhere_to_generally_accepted_naming_conventions.md)
* [10 Exceptions](10_exceptions/README.md)
   * [Item 69: Use exceptins only for exceptional conditions](10_exceptions/item_69_use_exceptins_only_for_exceptional_conditions.md)
   * [Item 70: Use checked exceptions for recoverable conditions and runtime exceptions for programming errors](10_exceptions/item_70_use_checked_exceptions_for_recoverable_conditions_and_runtime_exceptions_for_programming_errors.md)
   * [Item 71: Avoid unnecessary use of checked exceptions](10_exceptions/item_71_avoid_unnecessary_use_of_checked_exceptions.md)
   * [Item 72: Favor the use of standard exceptions](10_exceptions/item_72_favor_the_use_of_standard_exceptions.md)
   * [Item 73: Throw exceptions appropriate to the abstractions](10_exceptions/item_73_throw_exceptions_appropriate_to_the_abstractions.md)
   * [Item 74: Document all exceptins thrown by each method](10_exceptions/item_74_document_all_exceptins_thrown_by_each_method.md)
   * [Item 75: Include failure-capture information indetail messages](10_exceptions/item_75_include_failure-capture_information_indetail_messages.md)
   * [Item 76: Strive for failure atomicity](10_exceptions/item_76_strive_for_failure_atomicity.md)
   * [Item 77: Don't ignore exceptions](10_exceptions/item_77_dont_ignore_exceptions.md)
* [11 Concurrency](11_concurrency/README.md)
   * [Item 78: Synchronize access to shared mutable data](11_concurrency/item_78_synchronize_access_to_shared_mutable_data.md)
   * [Item 79: Avoid excessive synchronization](11_concurrency/item_79_avoid_excessive_synchronization.md)
   * [Item 80: Prefer executors, tasks, and streams to threads](11_concurrency/item_80_prefer_executors,_tasks,_and_streams_to_threads.md)
   * [Item 81: Prefer concurrency utilities to wait and notify](11_concurrency/item_81_prefer_concurrency_utilities_to_wait_and_notify.md)
   * [Item 82: Document thread safety](11_concurrency/item_82_document_thread_safety.md)
   * [Item 83: Use lazy initialization judiciously](11_concurrency/item_83_use_lazy_initialization_judiciously.md)
   * [Item 84: Don't depend on the thread scheduler](11_concurrency/item_84_dont_depend_on_the_thread_scheduler.md)
* [12 Serialization](12_serialization/README.md)
   * [Item 85: Prefer alternatives to Java serialization](12_serialization/item_85_prefer_alternatives_to_java_serialization.md)
   * [Item 86: Implement Serialzable with great caution](12_serialization/item_86_implement_serialzable_with_great_caution.md)
   * [Item 87: Condider using a custom serialized form](12_serialization/item_87_condider_using_a_custom_serialized_form.md)
   * [Item 88: Write readObject methods defensively](12_serialization/item_88_write_readobject_methods_defensively.md)
   * [Item 89: For instance control, prefer enum types to readResovle](12_serialization/item_89_for_instance_control,_prefer_enum_types_to_readresovle.md)
   * [Item 90: Consider serialization proxies instead of serialized instances](12_serialization/item_90_consider_serialization_proxies_instead_of_serialized_instances.md)
