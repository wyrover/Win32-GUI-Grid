# Microsoft Developer Studio Generated NMAKE File, Based on MFCGrid.dsp

!IF "$(OS)" == "Windows_NT"
NULL=
!ELSE
NULL=nul
!ENDIF

CPP=cl.exe
RSC=rc.exe

OUTDIR=.\Lib
INTDIR=.\Build
# Begin Custom Macros
OutDir=.\Lib
# End Custom Macros

ALL : "$(OUTDIR)\MFCGrid.lib"

CLEAN :
		-@erase "$(INTDIR)\GridCellUrl.obj"
        -@erase "$(INTDIR)\GridCellNumeric.obj"
        -@erase "$(INTDIR)\GridCellDateTime.obj"
        -@erase "$(INTDIR)\GridCellCheck.obj"
        -@erase "$(INTDIR)\GridCellCombo.obj"
        -@erase "$(INTDIR)\GridCell.obj"
        -@erase "$(INTDIR)\GridCellBase.obj"
        -@erase "$(INTDIR)\GridCtrl.obj"
        -@erase "$(INTDIR)\GridDropTarget.obj"
        -@erase "$(INTDIR)\InPlaceEdit.obj"
        -@erase "$(INTDIR)\StdAfx.obj"
        -@erase "$(INTDIR)\TitleTip.obj"
        -@erase "$(INTDIR)\vc60.idb"
        -@erase "$(INTDIR)\MFCGrid.pch"
        -@erase "$(OUTDIR)\MFCGrid.lib"

"$(OUTDIR)" :
    mkdir "$(OUTDIR)"

"$(INTDIR)" :
    mkdir "$(INTDIR)"

CPP=cl.exe
CPP_PROJ=/nologo /MD /W3 /GX /O2 /D "WIN32" /D "NDEBUG" /D "_WINDOWS" /D "_MBCS" /D"_WINDLL" /D"_USRDLL" /D "_AFXDLL" /D "_AFX_NOFORCE_LIBS" /Fo"$(INTDIR)\\" /Fd"$(INTDIR)\\" /FD /c

BSC32=bscmake.exe
BSC32_FLAGS=/nologo /o"$(OUTDIR)\MFCGrid.bsc"
BSC32_SBRS= \

LIB32=link.exe -lib
LIB32_FLAGS=/nologo /out:"$(OUTDIR)\MFCGrid.lib"
LIB32_OBJS= \
        "$(INTDIR)\TitleTip.obj" \
        "$(INTDIR)\InPlaceEdit.obj" \
        "$(INTDIR)\GridDropTarget.obj" \
        "$(INTDIR)\GridCtrl.obj" \
        "$(INTDIR)\GridCellBase.obj" \
        "$(INTDIR)\GridCell.obj" \
        "$(INTDIR)\GridCellNumeric.obj" \
		"$(INTDIR)\GridCellUrl.obj" \
        "$(INTDIR)\GridCellDateTime.obj" \
        "$(INTDIR)\GridCellCheck.obj" \
        "$(INTDIR)\GridCellCombo.obj" \
        "$(INTDIR)\StdAfx.obj"

"$(OUTDIR)\MFCGrid.lib" : "$(OUTDIR)" "$(INTDIR)" $(DEF_FILE) $(LIB32_OBJS)
    $(LIB32) @<<
  $(LIB32_FLAGS) $(DEF_FLAGS) $(LIB32_OBJS)
<<

.c{$(INTDIR)}.obj::
   $(CPP) @<<
   $(CPP_PROJ) $<
<<

.cpp{$(INTDIR)}.obj::
   $(CPP) @<<
   $(CPP_PROJ) $<
<<

.cxx{$(INTDIR)}.obj::
   $(CPP) @<<
   $(CPP_PROJ) $<
<<

.c{$(INTDIR)}.sbr::
   $(CPP) @<<
   $(CPP_PROJ) $<
<<

.cpp{$(INTDIR)}.sbr::
   $(CPP) @<<
   $(CPP_PROJ) $<
<<

.cxx{$(INTDIR)}.sbr::
   $(CPP) @<<
   $(CPP_PROJ) $<
<<

GridCell.cpp : \
        "CellRange.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "GridDropTarget.h"\
        "InPlaceEdit.h"\
        "StdAfx.h"\
        "TitleTip.h"


GridCellBase.cpp : \
        "CellRange.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "GridDropTarget.h"\
        "StdAfx.h"\
        "TitleTip.h"


GridCtrl.cpp : \
        "CellRange.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "GridDropTarget.h"\
        "MemDC.h"\
        "StdAfx.h"\
        "TitleTip.h"


GridDropTarget.cpp : \
        "CellRange.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "GridDropTarget.h"\
        "StdAfx.h"\
        "TitleTip.h"


InPlaceEdit.cpp : \
        "CellRange.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "GridDropTarget.h"\
        "InPlaceEdit.h"\
        "StdAfx.h"\
        "TitleTip.h"


StdAfx.cpp : \
        "StdAfx.h"


TitleTip.cpp : \
        "CellRange.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "GridDropTarget.h"\
        "StdAfx.h"\
        "TitleTip.h"

GridCellNumeric.cpp : \
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "InPlaceEdit.h"\
        "StdAfx.h"

GridCellDateTime.cpp : \
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "StdAfx.h"

GridCellCheck.cpp : \
        "GridCellCheck.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "StdAfx.h"

GridCellCombo.cpp : \
        "GridCellCombo.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "StdAfx.h"

GridCellUrl.cpp : \
        "GridCellUrl.h"\
        "GridCell.h"\
        "GridCellBase.h"\
        "GridCtrl.h"\
        "StdAfx.h"

SOURCE=GridCell.cpp

"$(INTDIR)\GridCell.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridCellBase.cpp

"$(INTDIR)\GridCellBase.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridCtrl.cpp

"$(INTDIR)\GridCtrl.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridDropTarget.cpp

"$(INTDIR)\GridDropTarget.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=InPlaceEdit.cpp

"$(INTDIR)\InPlaceEdit.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=StdAfx.cpp

"$(INTDIR)\StdAfx.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=TitleTip.cpp

"$(INTDIR)\TitleTip.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridCellNumeric.cpp

"$(INTDIR)\GridCellNumeric.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridCellDateTime.cpp

"$(INTDIR)\GridCellDateTime.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridCellCheck.cpp

"$(INTDIR)\GridCellCheck.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridCellCombo.cpp

"$(INTDIR)\GridCellCombo.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)

SOURCE=GridCellUrl.cpp

"$(INTDIR)\GridCellUrl.obj" : $(SOURCE) "$(INTDIR)"
        $(CPP) $(CPP_PROJ) $(SOURCE)
