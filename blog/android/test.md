test

标签（空格分隔）： android

列表项

测试一下GitHub和MarkDown编译器

 1. 总体规划
 2. 分化处理
 3. 总结
 

     if (tab == null) return;
        String tag = (String) tab.getTag();
        if (TAG_GOOD_APPRAISE.equals(tag)) {
            mCommentsType = GoodsCommentsProto.CommentsType.GOOD;
        } else if (TAG_MIDDLE_APPRAISE.equals(tag)) {
            mCommentsType = GoodsCommentsProto.CommentsType.MEDIUM;
        } else {
            mCommentsType = GoodsCommentsProto.CommentsType.BAD;
        }
        refreshData();

