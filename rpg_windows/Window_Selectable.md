Window_Selectable
===

# This document is generated by Python and has not already checked. There might be some mistakes.

# Father:
* [Window_Base](Window_Base.md)


# Functions:
* [drawAllItems()](#drawAllItems)
* [activate()](#activate)
* [processOk()](#processOk)
* [isCurrentItemEnabled()](#isCurrentItemEnabled)
* [isOpenAndActive()](#isOpenAndActive)
* [show()](#show)
* [setCursorFixed(cursorFixed)](#setCursorFixed)
* [hide()](#hide)
* [processPageup()](#processPageup)
* [itemRectForText(index)](#itemRectForText)
* [setCursorAll(cursorAll)](#setCursorAll)
* [isCancelTriggered()](#isCancelTriggered)
* [ensureCursorVisible()](#ensureCursorVisible)
* [itemWidth()](#itemWidth)
* [reselect()](#reselect)
* [isContentsArea(x, y)](#isContentsArea)
* [maxItems()](#maxItems)
* [callCancelHandler()](#callCancelHandler)
* [cursorDown(wrap)](#cursorDown)
* [isCancelEnabled()](#isCancelEnabled)
* [processHandling()](#processHandling)
* [cursorUp(wrap)](#cursorUp)
* [select()](#select)
* [row()](#row)
* [index()](#index)
* [cursorRight(wrap)](#cursorRight)
* [maxTopRow()](#maxTopRow)
* [updateArrows()](#updateArrows)
* [deactivate()](#deactivate)
* [hideHelpWindow()](#hideHelpWindow)
* [processCancel()](#processCancel)
* [cursorPagedown()](#cursorPagedown)
* [setBottomRow(row)](#setBottomRow)
* [resetScroll()](#resetScroll)
* [playOkSound()](#playOkSound)
* [topIndex()](#topIndex)
* [setHandler(symbol, method)](#setHandler)
* [processTouch()](#processTouch)
* [bottomRow()](#bottomRow)
* [isTouchOkEnabled()](#isTouchOkEnabled)
* [setHelpWindowItem(item)](#setHelpWindowItem)
* [clearItem(index)](#clearItem)
* [isHorizontal()](#isHorizontal)
* [playBuzzerSound()](#playBuzzerSound)
* [deselect()](#deselect)
* [maxPageRows()](#maxPageRows)
* [redrawCurrentItem()](#redrawCurrentItem)
* [redrawItem(index)](#redrawItem)
* [spacing()](#spacing)
* [topRow()](#topRow)
* [update()](#update)
* [showHelpWindow()](#showHelpWindow)
* [updateHelp()](#updateHelp)
* [itemRect(index)](#itemRect)
* [scrollUp()](#scrollUp)
* [initialize()](#initialize)
* [setHelpWindow(helpWindow)](#setHelpWindow)
* [updateInputData()](#updateInputData)
* [callHandler(symbol)](#callHandler)
* [isTouchedInsideFrame()](#isTouchedInsideFrame)
* [processWheel()](#processWheel)
* [processPagedown()](#processPagedown)
* [setTopRow(row)](#setTopRow)
* [drawItem(index)](#drawItem)
* [isOkTriggered()](#isOkTriggered)
* [isOkEnabled()](#isOkEnabled)
* [scrollDown()](#scrollDown)
* [cursorPageup()](#cursorPageup)
* [maxPageItems()](#maxPageItems)
* [itemHeight()](#itemHeight)
* [isCursorVisible()](#isCursorVisible)
* [callUpdateHelp()](#callUpdateHelp)
* [callOkHandler()](#callOkHandler)
* [refresh()](#refresh)
* [cursorFixed()](#cursorFixed)
* [hitTest(x, y)](#hitTest)
* [onTouch(triggered)](#onTouch)
* [updateCursor()](#updateCursor)
* [maxRows()](#maxRows)
* [maxCols()](#maxCols)
* [processCursorMove()](#processCursorMove)
* [cursorLeft(wrap)](#cursorLeft)
* [isHandled(symbol)](#isHandled)
* [cursorAll()](#cursorAll)
* [isCursorMovable()](#isCursorMovable)

# Members:
* _topId
* _stypeId
* _category
* _itemWindow
* _stayCount
* _maxDigits
* _lines
* _page
* _statusWindow
* _mode
* _cursorAll
* _waitMode
* _helpWindow
* _cursorFixed
* _spriteset
* _item
* _actor
* _handlers
* _currencyUnit
* _editWindow
* _touching
* _formationMode
* _waitCount
* _data
* _pendingIndex
* _baseLineStack
* _price
* _scrollX
* _scrollY
* _index
* _money
* _max
* _methods
* _number
* _shopGoods

# Details:
<p id=drawAllItems></p>

* drawAllItems()
	

<p id=activate></p>

* activate()
	

<p id=processOk></p>

* processOk()
	

<p id=isCurrentItemEnabled></p>

* isCurrentItemEnabled()
	

<p id=isOpenAndActive></p>

* isOpenAndActive()
	

<p id=show></p>

* show()
	

<p id=setCursorFixed></p>

* setCursorFixed(cursorFixed)
	

<p id=hide></p>

* hide()
	

<p id=processPageup></p>

* processPageup()
	

<p id=itemRectForText></p>

* itemRectForText(index)
	

<p id=setCursorAll></p>

* setCursorAll(cursorAll)
	

<p id=isCancelTriggered></p>

* isCancelTriggered()
	

<p id=ensureCursorVisible></p>

* ensureCursorVisible()
	

<p id=itemWidth></p>

* itemWidth()
	

<p id=reselect></p>

* reselect()
	

<p id=isContentsArea></p>

* isContentsArea(x, y)
	

<p id=maxItems></p>

* maxItems()
	

<p id=callCancelHandler></p>

* callCancelHandler()
	

<p id=cursorDown></p>

* cursorDown(wrap)
	

<p id=isCancelEnabled></p>

* isCancelEnabled()
	

<p id=processHandling></p>

* processHandling()
	

<p id=cursorUp></p>

* cursorUp(wrap)
	

<p id=select></p>

* select()
	

<p id=row></p>

* row()
	

<p id=index></p>

* index()
	

<p id=cursorRight></p>

* cursorRight(wrap)
	

<p id=maxTopRow></p>

* maxTopRow()
	

<p id=updateArrows></p>

* updateArrows()
	

<p id=deactivate></p>

* deactivate()
	

<p id=hideHelpWindow></p>

* hideHelpWindow()
	

<p id=processCancel></p>

* processCancel()
	

<p id=cursorPagedown></p>

* cursorPagedown()
	

<p id=setBottomRow></p>

* setBottomRow(row)
	

<p id=resetScroll></p>

* resetScroll()
	

<p id=playOkSound></p>

* playOkSound()
	

<p id=topIndex></p>

* topIndex()
	

<p id=setHandler></p>

* setHandler(symbol, method)
	

<p id=processTouch></p>

* processTouch()
	

<p id=bottomRow></p>

* bottomRow()
	

<p id=isTouchOkEnabled></p>

* isTouchOkEnabled()
	

<p id=setHelpWindowItem></p>

* setHelpWindowItem(item)
	

<p id=clearItem></p>

* clearItem(index)
	

<p id=isHorizontal></p>

* isHorizontal()
	

<p id=playBuzzerSound></p>

* playBuzzerSound()
	

<p id=deselect></p>

* deselect()
	

<p id=maxPageRows></p>

* maxPageRows()
	

<p id=redrawCurrentItem></p>

* redrawCurrentItem()
	

<p id=redrawItem></p>

* redrawItem(index)
	

<p id=spacing></p>

* spacing()
	

<p id=topRow></p>

* topRow()
	

<p id=update></p>

* update()
	

<p id=showHelpWindow></p>

* showHelpWindow()
	

<p id=updateHelp></p>

* updateHelp()
	

<p id=itemRect></p>

* itemRect(index)
	

<p id=scrollUp></p>

* scrollUp()
	

<p id=initialize></p>

* initialize()
	

<p id=setHelpWindow></p>

* setHelpWindow(helpWindow)
	

<p id=updateInputData></p>

* updateInputData()
	

<p id=callHandler></p>

* callHandler(symbol)
	

<p id=isTouchedInsideFrame></p>

* isTouchedInsideFrame()
	

<p id=processWheel></p>

* processWheel()
	

<p id=processPagedown></p>

* processPagedown()
	

<p id=setTopRow></p>

* setTopRow(row)
	

<p id=drawItem></p>

* drawItem(index)
	

<p id=isOkTriggered></p>

* isOkTriggered()
	

<p id=isOkEnabled></p>

* isOkEnabled()
	

<p id=scrollDown></p>

* scrollDown()
	

<p id=cursorPageup></p>

* cursorPageup()
	

<p id=maxPageItems></p>

* maxPageItems()
	

<p id=itemHeight></p>

* itemHeight()
	

<p id=isCursorVisible></p>

* isCursorVisible()
	

<p id=callUpdateHelp></p>

* callUpdateHelp()
	

<p id=callOkHandler></p>

* callOkHandler()
	

<p id=refresh></p>

* refresh()
	

<p id=cursorFixed></p>

* cursorFixed()
	

<p id=hitTest></p>

* hitTest(x, y)
	

<p id=onTouch></p>

* onTouch(triggered)
	

<p id=updateCursor></p>

* updateCursor()
	

<p id=maxRows></p>

* maxRows()
	

<p id=maxCols></p>

* maxCols()
	

<p id=processCursorMove></p>

* processCursorMove()
	

<p id=cursorLeft></p>

* cursorLeft(wrap)
	

<p id=isHandled></p>

* isHandled(symbol)
	

<p id=cursorAll></p>

* cursorAll()
	

<p id=isCursorMovable></p>

* isCursorMovable()
	

