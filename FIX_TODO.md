# EduNexus2.0 Error Fixes Tracker

## Backend Fixes
- [x] Fix duplicate AttendanceViewSet in school/views.py (already clean)
- [x] Fix duplicate ExamViewSet in school/views.py (already clean)
- [x] Fix dead code in ExamViewSet.publish_results (fixed AuditLog)
- [x] Fix undefined alumni_user in StudentViewSet.finalize_exit (removed reference)
- [ ] Fix ChatIntegrationViewSet reference in core/urls.py (verify)
- [ ] Fix integration_views.py class_obj -> assigned_class
- [ ] Fix accounts/urls.py serializer import

## Web Frontend Fixes
- [x] Fix dashboard/page.tsx Notice interface + role + window.location + any + apostrophe + useEffect
- [ ] Fix page.tsx (landing) duplicate footer/button + parsing
- [ ] Fix dashboard/layout.tsx duplicate nav items + finance block + role display
- [ ] Fix dashboard/alumni/page.tsx interface mismatches
- [ ] Fix ChatWindowSimple.tsx dead button + onKeyPress
- [ ] Fix components/ui/Button.tsx default type
- [ ] Fix admin/soc/page.tsx raw buttons + icon names
- [ ] Fix dashboard/chat/page.tsx API endpoints + WS port
- [ ] Fix SchoolSwitcher.tsx endpoint
- [ ] Fix IoTConfig.tsx WS host

## Mobile Frontend Fixes
- [ ] Fix MobileVoiceRecorder.tsx missing expo-av (add to package.json)
- [ ] Fix EnhancedMobileChatGroupList.tsx LinearGradient colors + Shadows
- [ ] Fix api.ts auth storage key consistency
- [ ] Fix MobileChatWindow.tsx API endpoints

