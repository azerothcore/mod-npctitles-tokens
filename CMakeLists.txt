CU_SET_PATH("CMAKE_NPC_TITLE_TOKENS_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/npc_title_tokens.cpp")

AC_ADD_SCRIPT_LOADER("NPC_Title_Tokens"      "${CMAKE_CURRENT_LIST_DIR}/src/loader.h")

message("-- NPC TITLE TOKENS CONFIGURED --")
