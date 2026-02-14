
## 🚀 Getting Started

1. **Clone or download** the HTML file
2. Open in any modern web browser
3. No build process or dependencies required
4. Toggle between Seller and Admin views using the header buttons

## 💡 Usage Guide

### Seller Workflow
1. View incoming orders in grid/list format
2. Accept pending orders (moves to "Accepted" status)
3. Wait for payment verification (admin only)
4. Process orders through status flow
5. Reject orders with reason if necessary
6. Generate invoices and packing slips for selected orders

### Admin Workflow
1. Monitor overall order volume and SLA compliance
2. Review alerts for high-risk and delayed orders
3. Verify payments for accepted orders
4. Run QC checks on processing orders
5. Override statuses when necessary (with reason)
6. Analyze insights for operational improvements

## 📱 Mobile Responsiveness

- Optimized viewport meta tag
- Responsive grid layouts
- Touch-friendly buttons (minimum 44px height)
- Collapsible filters on smaller screens
- Scrollable modals for long content

## 🔔 Notification System

Role-based notifications for:
- Order acceptance/rejection
- Payment verification
- Status updates
- SLA breaches
- Automatic document generation

## 📄 Document Generation

- **Invoices**: Auto-generated when payment is verified (Processing status)
- **Packing Slips**: Auto-generated when order reaches "Packed" status
- Manual generation also available via Payment dropdown

## 🧪 Demo Data

The dashboard comes pre-populated with 6 sample orders featuring:
- Multiple SKUs (SKU001, SKU002, SKU003)
- Various statuses (Pending → Delivered)
- Different risk levels and SLA statuses
- Customer notes and special instructions
- Product images from Unsplash

## 🎯 Target Users

- **Sellers/E-commerce Managers**: Day-to-day order processing
- **Admin/Supervisors**: Oversight, compliance monitoring, performance analysis
- **Operations Teams**: Quality control, bottleneck identification

## 🔧 Customization

To modify the sample data, edit the `generateMockData()` function. To adjust the color scheme, modify the CSS variables in the `<style>` section.

## 📋 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome for Android)
