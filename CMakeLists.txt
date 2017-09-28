add_library(poly2tri STATIC
	${CMAKE_CURRENT_SOURCE_DIR}/poly2tri/common/shapes.cc
	${CMAKE_CURRENT_SOURCE_DIR}/poly2tri/sweep/advancing_front.cc
	${CMAKE_CURRENT_SOURCE_DIR}/poly2tri/sweep/cdt.cc
	${CMAKE_CURRENT_SOURCE_DIR}/poly2tri/sweep/sweep.cc
	${CMAKE_CURRENT_SOURCE_DIR}/poly2tri/sweep/sweep_context.cc
)
