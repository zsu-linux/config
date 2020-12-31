------------
##  Vimium常用键映射
------------
    map u scrollUp                                # 向上滚动
                                                  # Scroll down
    map e scrollDown                              # 向下滚动
                                                  # Scroll up
    map n scrollLeft                              # 左滚动
                                                  # Scroll left
    map i scrollRight                             # 右滚动
                                                  # Scroll right
    map zn scrollToLeft                           # 滚动到最左侧
                                                  # Scroll all the way to the left
    map zi scrollToRight                          # 滚动到最右侧
                                                  # Scroll all the way to the right
    map U scrollPageUp                            # 上滚半页
                                                  # Scroll a half page down
    map E scrollPageDown                          # 下滚半页
                                                  # Scroll a half page down
    map k focusInput                              # 选择输入框
                                                  # Focus the first text input on the page
    map ] performFind                             # 查找下一个
                                                  # Cycle backward to the previous find match
    map [ performBackwardsFind                    # 查找上一个
                                                  # Cycle forward to the next find match
    map < goBack                                  # 返回网页上一层
                                                  # Go back in history
    map > goForward                               # 回到标签下一层
                                                  # Go forward in history
    map ,, moveTabLeft                            # 标签左移动
                                                  # Move tab to the left
    map .. moveTabRight                           # 标签右移动
                                                  # Move tab to the right
    map R reload                                  # 刷新
                                                  # Reload the page
    map N previousTab                             # 去左边一标签
                                                  # Go one tab left
    map I nextTab                                 # 去右边一个标签
                                                  # Go one tab right
    map H visitPreviousTab                        # 与本标签和上次标签切换
                                                  # Go to previously-visited tab 
    map a Marks.activateGotoMode                  # 跳转标记
                                                  # Go to a mark
    map dn closeTabsOnLeft                        # 删除左边所有标签
                                                  # Close tabs on the left
    map di closeTabsOnRight                       # 删除右边所有标签
                                                  # Close tabs on the right
    map dq closeOtherTabs                         # 删除除焦点标签所有标签
                                                  # Close all other tabs
    map gn firstTab                               # 跳转最左侧标签
                                                  # Go to the first tab
    map gi lastTab                                # 跳转最右侧标签
                                                  # Go to the last tab
    map gt toggleMuteTab                          # 静音
                                                  # Mute or unmute current tab
    map gh togglePinTab                           # 固定或取消固定当前标签
                                                  # Pin or unpin current tab
    map s LinkHints.activateMode                  # 本标签页打开链接
                                                  # Open a link in the current tab
    map S LinkHints.activateModeToOpenInNewTab    # 新标签页打开链duplicateTab 
                                                  # Open a link in a new tab
----------------
##  Vimium其它键映射参数
----------------
    # map ** scrollToTop                                   # 滚动到网页顶部
                                                           # Scroll to the top of the page
    # map ** scrollToBottom                                # 滚动到网页底部
                                                           # Scroll to the bottom of the page
    # map ** LinkHints.activateModeToCopyLinkUrl           # 复制页面内容链接
                                                           # Copy a link URL to the clipboard
    # map ** copyCurrentUrl                                # 复制标签链接
                                                           # Copy the current URL to the clipboard
    # map ** openCopiedUrlInCurrentTab                     # 当前标签页打开复制的链接
                                                           # Open the clipboard's URL in the current tab
    # map ** openCopiedUrlInNewTab                         # 新标签页打开复制的链接
                                                           # Open the clipboard's URL in a new tab
    # map ** goUp                                          # 返回到上一页
                                                           # Go up the URL hierarchy
    # map ** goToRoot                                      # 返回到根页
                                                           # Go to root of current URL hierarchy
    # map ** enterInsertMode                               # 插入模式
                                                           # Enter insert mode
    # map ** enterVisualMode                               # 视觉模式 
                                                           # Enter visual mode
    # map ** enterVisualLineMode                           #* 视线模式
                                                           # Enter visual line mode
    # map ** createTab                                     # 创建新标签页
                                                           # Create new tab
    # map ** LinkHints.activateModeWithQueue               # 不离开本标签焦点在新标签页打开链接
                                                           # Open multiple links in a new tab
    # map ** goPrevious                                    #*跟随标记链接
                                                           #*Follow the link labeled previous or < 
    # map ** goNext                                        #*按照标记的下一链接
                                                           #*Follow the link labeled next or >
    # map ** nextFrame                                     #*Select the next frame on the page
    # map ** mainFrame                                     #*Select the page's main/top frame
    # map ** Vomnibar.activateBookmarks                    # 本标签页打开书签链接
                                                           # Open a bookmark
    # map ** Vomnibar.activateBookmarksInNewTab            # 新标签页打开书签链接
                                                           # Open a bookmark in a new tab
    # map ** Vomnibar.activate                             # 本标签页打开搜索或地址
                                                           # Open URL, bookmark or history entry
    # map ** Vomnibar.activateInNewTab                     # 新标签页打开搜索或地址
                                                           # Open URL, bookmark or history entry in a new tab
    # map ** Vomnibar.activateEditUrl                      # 编辑当前标签页地址本页打开
                                                           # Edit the current URL
    # map ** Vomnibar.activateEditUrlInNewTab              # 编辑当前标签页地址新页打开
                                                           # Edit the current URL and open in a new tab
    # map ** Vomnibar.activateTabSelection                 # 在打开的标签页中搜索
                                                           # Search through your open tabs
    # map ** enterFindMode                                 # 查找内容
                                                           # Enter find mode
    # map ** duplicateTab                                  # 复制本标签页到新的标签页
                                                           # Duplicate current tab
    # map ** removeTab                                     # 关闭当前标签页
                                                           # Close current tab
    # map ** restoreTab                                    # 恢复最近关闭标签页
                                                           # Restore closed tab
    # map ** moveTabToNewWindow                            # 选项卡移动到新窗口
                                                           # Move tab to new window

------------
## 取消键映射
 -----------
    unmap j
    unmap <c-e>
    unmap d
    unmap h
    unmap l
    unmap zH
    unmap zL
    unmap r
    unmap gu
    unmap gU
    unmap <a-f>
    unmap <c-y>
    unmap [[
    unmap ]]
    unmap ` 
    unmap L
    unmap J
    unmap K
    unmap gT
    unmap g0
    unmap g$
    unmap ^
    unmap <a-p>
    unmap <a-m>
    unmap <<
    unmap >>
    unmap f
    unmap F
    unmap gf
    unmap gF

------------
## 搜索引擎
------------
		w: https://www.wikipedia.org/w/index.php?title=Special:Search&search=%s Wikipedia
		
		# More examples.
		#
		# (Vimium supports search completion Wikipedia, as
		# above, and for these.)
		#
		git: https://github.com/search?q=%s GitHub
		arch: https://wiki.archlinux.org/index.php/%s ArchWiki
		aur: https://aur.archlinux.org/packages/?O=0&SeB=nd&K=%s Aur
		bili: https://search.bilibili.com/all?keyword=%s Bilibili
		gz: https://translate.google.cn/?sl=zh-CN&tl=en&text=%s Google Translate zh-CN&en
		ge: https://translate.google.cn/?sl=en&tl=zh-CN&text=%s Google Translate en&zh-CN
		yd: http://www.youdao.com/w/eng/%s Youdao Translate
		g: https://www.google.com/search?q=%s Google
		d: https://www.baidu.com/s?ie=utf-8&wd=%s Baidu
		# l: https://www.google.com/search?q=%s&btnI I'm feeling lucky...
		y: https://www.youtube.com/results?search_query=%s Youtube
		# gm: https://www.google.com/maps?q=%s Google maps
		b: https://www.bing.com/search?q=%s Bing
		# d: https://duckduckgo.com/?q=%s DuckDuckGo
		# az: https://www.amazon.com/s/?field-keywords=%s Amazon
		# qw: https://www.qwant.com/?q=%s Qwant
