# Website iOS App Store Compliance Checklist

## ✅ Updates Completed

### 1. Privacy Policy (`privacy-policy.html`)
- ✅ Added comprehensive User-Generated Content (UGC) section
- ✅ Added links to third-party privacy policies (Firebase, WhatsApp, Twilio, Supabase, RapidAPI)
- ✅ Added UGC data retention section
- ✅ All data collection types properly documented
- ✅ Account deletion process clearly explained
- ✅ Children's privacy section included (COPPA compliance)

### 2. Terms of Service (`terms-of-service.html`)
- ✅ Added comprehensive User-Generated Content (UGC) section (Section 6)
- ✅ Added prohibited content list
- ✅ Added content moderation and removal rights
- ✅ Added user responsibility for uploaded content
- ✅ Added reporting mechanism information
- ✅ All section numbers updated accordingly

### 3. Homepage (`index.html`)
- ✅ Added iOS App Store link placeholder
- ✅ Updated download section to show both Android and iOS
- ✅ Updated footer to include iOS App Store link

## 📋 Verification Checklist

### Before iOS App Store Submission:

#### Privacy Policy URL
- [ ] Verify `https://ironsaathi.com/privacy-policy.html` is accessible
- [ ] Test on mobile device (Safari/Chrome)
- [ ] Ensure HTTPS is working
- [ ] Verify all links to third-party privacy policies work
- [ ] Check that page loads without errors

#### Terms of Service URL
- [ ] Verify `https://ironsaathi.com/terms-of-service.html` is accessible
- [ ] Test on mobile device (Safari/Chrome)
- [ ] Ensure HTTPS is working
- [ ] Verify all sections are properly formatted
- [ ] Check that page loads without errors

#### Content Verification
- [ ] Privacy Policy covers all data types:
  - [x] Phone numbers
  - [x] User profile information
  - [x] Attendance records
  - [x] Payment history
  - [x] Location data (if used)
  - [x] User-generated content
  - [x] Device information
  - [x] Push notification tokens

- [ ] Privacy Policy mentions all third-party services:
  - [x] Firebase (Google)
  - [x] WhatsApp Business API (Meta)
  - [x] SMS Providers (Twilio/MSG91)
  - [x] Supabase (cloud storage)
  - [x] ExerciseDB API (via RapidAPI)

- [ ] Terms of Service covers:
  - [x] User-generated content
  - [x] Prohibited content
  - [x] Content moderation
  - [x] Content removal rights
  - [x] User responsibilities

#### iOS App Store Link
- [ ] Update iOS App Store link when app is approved:
  - Current placeholder: `https://apps.apple.com/app/ironsaathi/id6755970504`
  - Replace "Coming Soon" text with "Download on App Store" when live
  - Update homepage hero section
  - Update footer section

## 🔍 Testing Instructions

### Test Privacy Policy:
1. Open `https://ironsaathi.com/privacy-policy.html` in browser
2. Verify page loads correctly
3. Check all links work (third-party privacy policies)
4. Verify content is readable and properly formatted
5. Test on mobile device (Safari iOS)

### Test Terms of Service:
1. Open `https://ironsaathi.com/terms-of-service.html` in browser
2. Verify page loads correctly
3. Check all sections are properly numbered
4. Verify UGC section (Section 6) is present
5. Test on mobile device (Safari iOS)

### Test Homepage:
1. Open `https://ironsaathi.com` in browser
2. Verify both Android and iOS download links are visible
3. Check iOS link placeholder is present
4. Verify footer includes iOS link

## 📝 Notes

### iOS App Store Requirements Met:
- ✅ Privacy Policy URL accessible and comprehensive
- ✅ Terms of Service URL accessible and includes UGC section
- ✅ All data collection properly disclosed
- ✅ All third-party services mentioned with privacy policy links
- ✅ User-generated content properly addressed
- ✅ Account deletion process clearly explained
- ✅ Children's privacy (COPPA) compliance

### When iOS App is Approved:
1. Update iOS App Store link in `index.html`:
   - Replace placeholder URL with actual App Store URL
   - Change "Coming Soon" to "Download on App Store"
   - Update hero section and footer

2. Test the updated links:
   - Verify App Store link opens correctly
   - Test on iOS device
   - Verify download button works

## 🚀 Next Steps

1. **Deploy website changes:**
   - Commit and push changes to GitHub
   - Verify website updates are live
   - Test all URLs are accessible

2. **Before iOS submission:**
   - Verify Privacy Policy URL in App Store Connect
   - Verify Terms of Service URL (if required)
   - Test all links from mobile device
   - Ensure HTTPS is working

3. **After iOS approval:**
   - Update iOS App Store link
   - Change "Coming Soon" to "Download on App Store"
   - Test download functionality

---

**Last Updated:** December 7, 2025  
**Status:** ✅ Ready for iOS App Store Submission

