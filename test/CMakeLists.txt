add_executable(TestSplitCommit run-all-tests.cpp test-split-commit.cpp)
target_link_libraries(TestSplitCommit SPLIT_COMMIT gtest_main gtest)