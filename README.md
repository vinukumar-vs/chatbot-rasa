# chatbot-rasa
RASA for chatbot


Testing Git commit message hook working

Git commit regex verify 
/(^(Issue)\s+(#)([A-Za-z]|[0-9]){1,})(\s(feat|fix|docs|style|refactor|test|chore|merge))(\([a-zA-Z0-9 _,.-]+?\))?: .{1,59}/g

ex: Issue #1 feat: Testing git commit message hook test


[[ "Issue #AS-1 fix: message" =~ ^((^(Issue+)\s+(#)([A-Za-z]|[0-9]){1,}).+?(\s(feat|fix|docs|style|refactor|test|chore|merge))(\([a-zA-Z0-9 _,.-]+?\))?:.{1,59})$ ]] && echo 1 || echo 0