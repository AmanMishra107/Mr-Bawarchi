# Mr. Bawarchi

> Sealed in copper, cooked on dum, opened at the table.
> Hyderabadi dum biryani & charcoal tandoor, Hyderabad.

## Development

```sh
bun install
bun run dev
```

The app will run locally at `http://localhost:8080/`.

## Architecture & Configuration

- **Brand Details**: All business details (restaurant name, timings, address, phone, menu) live in [`src/lib/site.ts`](src/lib/site.ts).
- **Media Assets**: Media references live in [`src/lib/media.ts`](src/lib/media.ts).
- **Styles**: Custom theme in [`src/styles.css`](src/styles.css) with Tailwind CSS v4.
