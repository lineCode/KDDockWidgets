#
# This file is part of KDDockWidgets.
#
# SPDX-FileCopyrightText: 2020 Klarälvdalens Datakonsult AB, a KDAB Group company <info@kdab.com>
# Author: Sergio Martins <sergio.martins@kdab.com>
#
# SPDX-License-Identifier: GPL-2.0-only OR GPL-3.0-only
#
# Contact KDAB at <info@kdab.com> for commercial licensing options.
#

find_package(Qt5Test)
add_executable(tst_multisplitter tst_multisplitter.cpp)
target_link_libraries(tst_multisplitter kddockwidgets_multisplitter Qt5::Test)
set_compiler_flags(tst_multisplitter)
